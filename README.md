# **IRCTC Stock Price Prediction Using ARIMA Model**

This project involves building a time series forecasting model to predict future stock prices of 
Indian Railway Catering and Tourism Corporation uses the ARIMA ( AutoRegressive Integrated Moving Average) model. The ARIMA model is trained on historical stock price data and is used to forecast
future prices through static multistep forecasting and dynamic walk-forward (rolling) prediction.

- Key steps include:
1. Data downloaded from Yahoo Finance.
2. Model Selection and parameter tuning (ARIMA(p,d,q)).
3. Performing static forecasts for 123 future steps.
4. Implementing walk-forward validation to simulate real-time prediction.
5. Visualization of actual vs predicted stock prices with confidence intervals.
