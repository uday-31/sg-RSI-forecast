# sg-RSI-forecast
Using various benchmark time series forecasting methods in R to forecast Singapore's Retail Sales Index

This project was done for the requirements of the module HE3022 Econometric Modeling and Forecasting, along with my group members Heena Agarwal, Gopal Agarwal, and Manasi Murali.

# Introduction

The Retail Sales Index is an important indicator of the health of an economy.

In this project, after conducting preliminary exploratory analysis of Singapore's RSI data, we used various methods to forecast its values. We compared the different methods, performed residual diagnostics, and used the best methods to make a forecast for the next 5 years starting 2020.

# Exploratory analysis

We plotted the time series, seasonal, and subseries plots to study the trend, seasonality, and cyclicity of the data, and the ACF and lag plots to look at the autocorrelation of the data.

# Benchmark methods

The benchmark methods compared included naive, seasonal naive, random walk with drift, and STL-naive forecasting.

# Exponential smoothing models

The exponential smoothing models compared included Holt's method, Holt-Winters multiplicative and additive methods, Holt-Winters seasonal method, ETS, and STL-ETS methods.

# ARIMA models

The ARIMA models compared included an auto-ARIMA, and an STL-ARIMA model.

# Linear and dynamic regression

We used regressors like per capital GNI, number of residents, average CPF contribution rates, total Certificate of Entitlement (COE) quota, and dummy variables for months.

The regression models compared included linear regression, dynamic regression with ARIMA errors, and dynamic regression with ARIMA errors and lagged predictors.

# Making forecasts

The three best models - ARIMA, Holt-Winters multiplicative, and STL-ETS - were used to make an ensemble model with custom weights to make the final forecasts. Prediction intervals were generated using bootstrapping.
