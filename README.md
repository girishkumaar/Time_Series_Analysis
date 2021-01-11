# Time_Series_Analysis
Time series analysis for future prediction of different elements

# A Gentle Introduction to SARIMA for Time Series Forecasting in Python
Autoregressive Integrated Moving Average, or ARIMA, is one of the most widely used forecasting methods for univariate time series data forecasting.
Although the method can handle data with a trend, it does not support time series with a seasonal component.
An extension to ARIMA that supports the direct modeling of the seasonal component of the series is called SARIMA.

# Trend Elements
There are three trend elements that require configuration.
They are the same as the ARIMA model; specifically:
p: Trend autoregression order.
d: Trend difference order.
q: Trend moving average order.

# Seasonal Elements
There are four seasonal elements that are not part of ARIMA that must be configured; they are:
P: Seasonal autoregressive order.
D: Seasonal difference order.
Q: Seasonal moving average order.
m: The number of time steps for a single seasonal period.

SARIMA(p,d,q)(P,D,Q)m
