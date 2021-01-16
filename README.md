# LSTM_Finance_Stock_Price_Predictions
Stock Predictions Using ARIMA And LSTM
Using Standard & Poor's 500 Index Stock prices data , predict opening stock prices using below approach:
  Prediction using ARIMA by using backfill of data for weekend stock prices, Augmented Dickey Fuller Test to determine new feature column open_price_difference is stationary, then use the ACF plot to find the MA (q) term and PACF plot to find the AR (p) term and ue lag term to apply ARIMA model
  Predictions using LSTM model by Preprocess data using signal processing techniques using PyWavelets and then used Vanilla architecture on Open, FilteredOpen and ZeroMeanFilteredOpen to find out which gives the best predictions
  
