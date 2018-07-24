# Earnings Call Transcripts and Risk

The task here is to forecast stock return volatility for the trading day immediately following an earnings call. The inputs are pieces of text, in particular earnings transcripts. The outputs are the labels +1 or -1 for volatility either going up or down after the call. The Machine Learning classifiers used here were Support Vector Machines, Neural Networks, Random Forests, and XGBoost. Each classifier's accuracy performance was backtested over a period of around 6 years. 

## Data

Earnings Call Transcripts for the top 50 holdings of the SP500 were obtained from [seekingalpha](https://seekingalpha.com/) from 2012-01-01 to 2018-07-01, totaling around 1250 transcripts. The code for this web scraping can be found in [browser_automate.py](https://github.com/yaroverg/transcripts-risk/blob/master/browser_automate.py) where mainly the [selenium](https://pypi.org/project/selenium/) package was used. 

Stock price data was obtained mostly via the [Quandl Python Module](https://www.quandl.com/tools/python) and the code for that can be found in [quandl_price_data.py](https://github.com/yaroverg/transcripts-risk/blob/master/quandl_price_data.py) and some missing data was filled in from Yahoo Finance. 

## Volatility

TODO: Write usage instructions

## Transcript processing and Feature extraction 

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Machine Learning Classifiers

TODO: Write history

## Feature Importances

TODO: Write credits

## something

TODO: Write license
