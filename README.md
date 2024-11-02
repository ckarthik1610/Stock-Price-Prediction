# Stock Price Predictor Using Regression

This project uses Linear regression to predict the stock close price for the next day. It uses yahoo finance data which is retreived using the library "yfinance". The data is used to train the linear regression model and saved using the ".h5" format. An example model has been trained with the stock price data on the company Apple.Inc with the ticker value "AAPL". The ticker value is the value assigned to each stock and is used to retreive the stock data, with the right ticker value you can assess any data through the yfinance library. 

There stock price and predicted price are shown below -
![image](https://github.com/user-attachments/assets/180b63d7-0042-49ff-8749-93db40fcadb8)

This prediction system uses factors like High, Low, Open, Close, Adj Close and Volume data to predict the Close price of next day. There are other factors too that does impact the stock considering the volatility of the market. This system can predict the close price of any stock with the ticker value as input. 
