# TIME SERIES ANALYSIS OF VISITORS TO GEORGIA 

## INTRODUCTION:
Georgia country becomes one of the top travel destinations in recent years. Understanding
the characteristics of the time series representing international visits to the country
provides valuable insights for business. In this project, the number of visitors that would
probably turn up in coming years is calculated using SARIMA, Winters and XGBOOST
models. The outcome is used in budgeting and revenue planning for one of the local hotels.
Some of the most effective forecasting methods in time series analysis include SARIMA and
WINTERS Exponential Smoothing . The Root Mean Square Error (RMSE), Mean Absolute
Percentage Error (MAPE), and Mean Absolute Square Error are used to measure the
accuracy of the fitted models (MAE)

**SARIMA MODEL:**

Autoregressive Integrated Moving Average, or ARIMA, is one of the most widely used
forecasting methods for univariate time series data forecasting. Although the method can
handle data with a trend, it does not support time series with a seasonal component. An
extension to ARIMA that supports the direct modeling of the seasonal component of the
series is called SARIMA. The extension of ARIMA known as Seasonal Autoregressive
Integrated Moving Average, or Seasonal ARIMA, specifically supports univariate time series
data with a seasonal component. There are three trend components that need setting up.
They match the ARIMA model in the following ways: p: Order of trend autoregression. d:
Order of trend difference. q: Order of the trend moving average. There may be many
different parameters and term combinations in seasonal ARIMA models. As a result, it is
appropriate to test out a variety of models when fitting them to data and then

**WINTERS SMOOTHING:**

Numerous previous data are compressed using exponential smoothing via the Holt-Winters
method in order to anticipate “typical” values for the present and the future. Exponential
smoothing is the process of “smoothing” a time series using an exponentially weighted
moving average (EWMA). The three order parameters of a Holt-Winters model are alpha,
beta, and gamma. The level smoothing coefficient is specified by alpha. The coefficient for
the trend smoothing is specified by beta. The coefficient for the seasonal smoothing is
specified by gamma. The type of seasonality has a parameter as well: seasonality that is
additive and has a fixed number of seasons. Seasonality that changes by a factor
multiplicatively.

## OBJECTIVE:

• A comparative study is performed to forecast the Visitors count in Georgia for the
next five years using ARIMA and Holts exponential with the help of accuracy
measures.

## DATA SOURCE:

A time-series approach is used in the monthly wise Visitors data from 2011 to 2020 Jan,
from the official website of Georgian tourism department. -
[https://knoema.com/atlas/Georgia/datasets]
