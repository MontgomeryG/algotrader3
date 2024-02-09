This project aims to create a profitable trading bot.

It will use U.S. stock market equities.

It will use neural networks to make trading decisions.

 The "TradingAlgo.ipynb" document is where the discussion begins.

Required Libraries:
numpy
pandas
hvplot.pandas
pathlib
finta 
plotly.graph_objects 
os
requests
dotenv 
alpaca_trade_api 
scipy 
dotenv
sklearn
keras


The below is a start at using 3 machine learning models to create long/short signals in instances where the stock trades in a range. We will look to employ the algorithm during instances defined with the following characteristics:
- Large-cap stocks (they tend to offer ranges intraday that "scalpers" take advantage of. I'm willing to bet an algo can learn how to scalp like those traders or even better.)
- During times of low volatility. Low Volatility is essentially what we mean when we say, "the stock is trading in a range"; when the price action of a stock can be considered "range-bound".  This is typically in the middle of the day when there is less volume in the markets. We can visualize the average volume given time of day later on in this project. 

We will start with the above, keeing it simple.


Our next step is to choose the variables that we will feed the algorithm. Remember that these variables will be based on a stock's Open Low High and Close (OHLC), and Volume, for now...