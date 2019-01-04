# predict-stock-price
This is the challenge for stock price prediction by Siraj on [Youtube](https://www.youtube.com/watch?v=9gBC9R-msAk&feature=youtu.be).

# Overview

For the challenge, I used the finance data of Volkswagen with period of a year starting from Jan 4 2018. You can find it here [Data](https://finance.yahoo.com/quote/VOW3.DE/historyperiod1=1514995200&period2=1546531200&interval=1d&filter=history&frequency=1d).
I scaled the data into minimum and maximum values of 0 to 1. Next, I retrieved the latest tweets about Volkswagen and identified them to be positive before moving on. Also, I chose to go with two layers of lstm, with last 30 records as timesteps.

# Dependencies
keras, sklearn, numpy, pandas, tweepy, nltk, textblob and matplotlib for plotting

# Usage
Just run

# Notes
It is predicting based on the data, not built to forecast yet.

# Credits 
1. [Siraj](https://github.com/llSourcell)
