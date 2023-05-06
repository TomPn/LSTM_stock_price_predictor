# LSTM Stock Price Predictor

This predictor utilizes a **regression model** composed of a single layer **LSTM** network and fully connected network to predict the next day's stock price with preivous 30 days of data.
It's an attempt to apply deep learning algorithm to the prediction of the future stock price.
The hyperparameters are tuned using keras tuner so that the result has the **lowest validation mean absolute error**.
**Features** used: US Price Index, Interest Rate, Consumer Price Index, CBOE Volatility Index, Open Price, and Close Pirce.

The default stock in the algorithm is S&P 500, but it can be freely changed to any stock ticker in the market :)

The script runs on **Google Colab**, so feel free to download it and **run it yourself**!
