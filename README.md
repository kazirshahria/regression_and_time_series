# Regression Analysis and Time Series Analysis

## Overview
Conducting predictive analysis on data using Python and statistical methods such as regression and time series.

- [Car Price Prediction Dataset](https://www.kaggle.com/datasets/hellbuoy/car-price-prediction)
- [Netflix's Stock Price](https://www.kaggle.com/datasets/mayankanand2701/netflix-stock-price-dataset)

## Regression
Building regression models that can be for real world usages.

**Steps:**
- Fitting OLS Models
- Visualizing Relationships and Linear Models
- Hypothesis Testing
- Plotting Residuals
- More Tests


## Time Series Analysis
Conduct time series analysis on Netflix stock price data. The notebook `time_series.ipynb` contains the research and analysis conducted on the Netflix stock price.

---
### Autoregressive (AR) Model
The AR model did not perform well on Netflix's closing price.

**Key Notes:**
- Transformed the data using Box Cox.
- Subset the data to the last 90-180-365 days.
- Determined performance of the AR model using metrics such as MAPE and MSE.

---
### Autoregressive Integrated Moving Average (ARIMA) Model
The ARIMA model was able to perfrom well on Netflix's closing price, but the model might not be able to predict future prices.

**Key Notes:**
- Transformed the data using differencing.
- Conduct Augmented Dickey-Fuller Test.
- Determine P and Q values using PACF and ACF plots.
