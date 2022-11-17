# SARIMA model for Time Series Demand Forecasting

In this project the SARIMA based statstical model is used to predict the future car sales by analysing the Paterns & Trends in the historical data.

ARIMA, or “Autoregressive Integrated Moving Average, is a method for forecasting univariate time series data. It can handle both autoregressive and moving average data. The integrated element uses differencing to transform non-stationary time-series processes to stationary, allowing the method to support trending time series data. ARIMA has the drawback of not supporting seasonal data. That is a time series with a cycle that repeats. ARIMA anticipates data that is either not seasonal or has had the seasonal component removed, for as by using seasonal differencing methods”.

SARIMA, or “Seasonal Autoregressive Integrated Moving Average is an extension of ARIMA that can handle univariate time series data with a seasonal component. It adds 
three new hyperparameters for the seasonal component of the series: autoregression (AR), differencing (I), and moving average (MA), as well as an additional parameter for the seasonality period. Additional seasonal parameters are added to the ARIMA model to create a seasonal ARIMA model. The seasonal component of the model contains terms that are quite similar to the non-seasonal components, but they feature seasonal backshifts”

## The following is the general procedure for SARIMA models: 

1. Time Series Data Visualization.
2. Make the data in the time series stationary.
3. Draw the Auto-Correlation and Correlation Charts.
4. Create an ARIMA Model or Seasonal ARIMA using the data. 
5. Make a prediction using the model.

![image](https://user-images.githubusercontent.com/94454275/202422073-4795e248-a004-4728-887f-e6095f45f0b4.png)
