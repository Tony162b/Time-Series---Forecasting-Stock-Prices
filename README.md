# Time-Series---Forecasting-Stock-Prices
Used Time Series to forecast 24 months stock price of Amazon products and subscriptions. This dataset which is in excel format consists of monthly average stock closing prices of Amazon over a period of 12 years from 2006 to 2017. We must build a time series model using the AR, MA, ARMA and ARIMA models to forecast the stock closing price of Amazon.
These four models were used to determine which one performs better at the end
Augmented Dickey Fuller test (ADF Test) was used to test whether the given Time series was stationary or not.
Applied the following methods to convert a non-stationary series into a stationary one:
•	Log Transformation
•	By differencing the series (lagged series)
Plot the auto-correlation function and partial auto-correlation function to get p and q values for AR, MA, ARMA, and ARIMA models
Root mean square error (RMSE) was used to measure the differences between values predicted by various models
