
# Natural Gas Stock Prediction

This project analyzes the time series data of natural gas stock prices using various techniques including data exploration, stationarity testing, GARCH modeling, residual analysis, and forecasting.
The dataset used in this project provides comprehensive information on stock prices related to oil, gas, and other fuels. For the purpose of this analysis, only the prices of natural gas have been considered.

## Overview
A time series dataset is a collection of data points that are recorded and ordered sequentially over time. In other words, it is a series of observations or measurements taken at successive points in time, typically at regular intervals.
Time series datasets can arise in various domains such as finance, economics, meteorology, science, and many other fields where data is collected over time. These datasets are valuable for analyzing patterns, trends, seasonality, and cycles, as well as for forecasting future values based on historical data.
## Methodology
The analysis follows these steps:

1. Data Exploration: The natural gas stock price data is loaded, and time series plots and histograms are generated to visualize the data distribution.
2. Stationarity Test: The stationarity of the time series data is tested using the Augmented Dickey-Fuller (ADF) test.
3. GARCH Model: A Generalized Autoregressive Conditional Heteroskedasticity (GARCH) model is fitted to the data to capture the volatility clustering present in financial time series.
4. Residual Analysis: The residuals of the fitted GARCH model are analyzed using various diagnostic plots and tests. The Ljung-Box test indicates that the residuals are not serially correlated, suggesting that the model is adequate.
5. Forecasting: The fitted GARCH model is used to forecast the natural gas stock prices for the next 10 periods. The forecasts are plotted along with the actual data and confidence intervals.
## Results
The fitted GARCH model captures the volatility clustering present in the data, and the residual analysis suggests that the model is adequate. The forecasting component provides insights into the future behavior of natural gas stock prices based on the historical data.
## R Packages Used
1. readxl: For reading Excel files

2. tseries: For time series analysis

3. rugarch: For fitting GARCH models

4. forecast: For forecasting and model diagnostics
