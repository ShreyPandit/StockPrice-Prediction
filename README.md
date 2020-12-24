# StockPrice-Prediction<br>
Time series model for predicting the stock price. The Example is taken on the share of Nifty.<br>
# Model <br>
The model consists of LSTM and dropout.  LSTM are used because they are capable of remembering the past values and use them to predict the future value. Here lookback is 90 days. <br>
<img src="./images/Model.png" alt="result image" width="300" height="200" > <br>
# Loss <br>
The loss function is mean squared error and optimizer is adam <br>
<img src="./images/Loss.png" alt="result image" width="300" height="200" > <br>
