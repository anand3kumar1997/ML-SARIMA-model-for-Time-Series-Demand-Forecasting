# SARIMA model for Time Series Demand Forecasting

In this project, the SARIMA-based statistical model is used to predict future car sales by analyzing the patterns & Trends in the historical data.

ARIMA stands for Autoregressive Integrated Moving Average Model. It belongs to a class of models that explains a given time series based on its own past values i.e. its own lags and the lagged forecast errors. The equation can be used to forecast future values. 

SARIMA stands for Seasonal Autoregressive Integrated Moving Average, it is an extension of ARIMA that explicitly supports univariate time series data with a seasonal component. It adds three new hyperparameters to specify the autoregression (AR), differencing (I) and moving average (MA) for the seasonal component of the series, as well as an additional parameter for the period of the seasonality. The seasonal part of the model consists of terms that are very similar to the non-seasonal components of the model, but they involve backshifts of the seasonal period.

## The following is the general procedure for SARIMA models: 

1. Time Series Data Visualization.
2. Make the data in the time series stationary.
3. Draw the Auto-Correlation and Correlation Charts.
4. Create an ARIMA Model or Seasonal ARIMA using the data. 
5. Make a prediction using the model.

![image](https://user-images.githubusercontent.com/94454275/202422073-4795e248-a004-4728-887f-e6095f45f0b4.png)

## Libraries used

1. pandas
2. numpy
3. matplotlib
4. statsmodels
5. pmdarima
6. warnings
