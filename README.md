This project aims to create a profitable trading bot.

It will use U.S. stock market equities.

It will use neural networks to make trading decisions.

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


This models aims to create long/short signals in instances where the stock trades with low volatility. 
- During times of low volatility... Low Volatility is essentially what we mean when we say, "the stock is trading in a range"; when the price action of a stock can be considered "range-bound".  This is typically in the middle of the day when there is less volume in the markets. There are many visualizations that demonstrate this phenomenon out there on the web. 

- Large-capitalization stocks tend to offer ranges in the middle of the trading day; such as AAPL, AMD, 



We will start with the above, keeping it simple, then seek to improve with each new iteration.


Our next step is to choose the variables that we will feed the algorithm; variables be based on each stock's Open Low High and Close (OHLC), and Volume, for now.

 Please start at 1_nn_data_aquisition.ipynb.