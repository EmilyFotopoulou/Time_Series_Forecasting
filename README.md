# Time_Series_Forecasting
<img width="2040" height="953" alt="image" src="https://github.com/user-attachments/assets/886a621d-c9f6-414d-a1f0-197284cc627e" />


# Overview
A solution to Time Series Analysis, including Forecasting using [**ARIMA.**](https://www.statsmodels.org/stable/generated/statsmodels.tsa.arima.model.ARIMA.html)

You can run the whole analysis in [ **colab.** ](https://colab.research.google.com/drive/1b-voCdRjiX6jaUR8VXJrIlRHdeCEzjCz?usp=sharing#scrollTo=9bd55caf) 

Using datafile:<ins>**US_births_2000-2014_SSA.csv**</ins>


# Why do Seasonality Analysis?
Seasonality analysis helps uncover repeating patterns in data (e.g., weekly sales spikes, yearly weather changes). Identifying seasonality makes forecasts more accurate because it separates predictable variations from random noise.

## What is ARIMA?
Autoregressive Integrated Moving Average (ARIMA) is a statistical model commonly used for time series forecasting. It combines three elements: autoregression (AR), differencing (I) to make data stationary, and moving averages (MA) to capture error patterns.

### Explaining ACF and PACF
**Autocorrelation Function (ACF)** -> measures how <ins>correlated a time series is with itself<ins> at different time lags.

**Partial Autocorrelation Function (PACF)** -> shows how much a past value is related to the current value <ins>after removing the effect of other lags<ins>.

# Benefits of Forecasting
Time series forecasting is valuable across fields, from predicting stock market trends and energy demand to planning retail inventory and anticipating weather patterns. Accurate forecasts support better decision-making, reduce costs, and help organizations prepare for the future.

E.g. A supermarket chain can use time series forecasting to predict weekly demand for fresh produce. By identifying seasonal spikes (e.g., higher fruit sales in summer) and trends, the store can optimise inventory, reduce waste, and avoid stockouts; leading to better customer satisfaction and cost savings.
