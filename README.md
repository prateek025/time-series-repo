# Time Series Forecasting Repository

## I. Repository Overview
- This repository contains notebooks covering different Machine Learning techniques ranging from statistics models such as *ETS* to deep learning models such as *RNN* to make forecasts on time series data. Some notebooks cover forecasting on univariate time series data, while others on multivariate time series data.
- Currently 4 notebooks are available in this repository:
  1. `time_series_ets_tbats.ipynb`
  2. `time_series_arima.ipynb`
  3. `time-series-rnn.ipynb`
  4. `time_series_regression.ipynb`

## II. Tutorial notebooks details
1. **`time_series_ets_tbats.ipynb`**
   - **Time Series Forecasting using ETS and TBATS models** : This tutorial covers developing multiple **Error,Trend,Seasonal**:`ETS` and **Trigonometric seasonality, Box-Cox transformation, ARMA errors, Trend and Seasonal**:`TBATS` models to predict forecasts for a time series data.
   - Monthly anti-diabetic drug sales : [a10](https://rdrr.io/cran/fpp/man/a10.html) dataset from the `fpp` package in R language has been taken for model development.

2. **`time_series_arima.ipynb`**
   - **Time Series Forecasting using ARIMA models** : This tutorial covers developing multiple **Autoregressive Integrated Moving Average**:`ARIMA` models to predict forecasts for a time series data.
   - Monthly anti-diabetic drug sales : [a10](https://rdrr.io/cran/fpp/man/a10.html) dataset from the `fpp` package in R language has been taken for model development.

3. **`time_series_rnn.ipynb`**
   - **Time Series Forecasting using Recurrent Neural Network** : This tutorial covers developing RNN models to predict forecasts for a time series data. All model development has been done under `Tensorflow` framework.
   - Monthly anti-diabetic drug sales : [a10](https://rdrr.io/cran/fpp/man/a10.html) dataset from the `fpp` package in R language has been taken for model development.
   - Different combinations of architecture (single vs multiple layers of `SimpleRNN`) and parameters(`Adam` vs `SGD` optimizer) were tried to build multiple RNN models.

4. **`time_series_regression.ipynb`**
   - **Time Series Forecasting using Regression** : This tutorial covers developing a Regression model, `Light Gradient Boosting Regresison` model in this case, to predict forecasts for a multi-variate time series data.
   - [uschange](https://rdrr.io/github/robjhyndman/fpp/man/uschange.html) dataset from the `fpp` package in R language has been taken for model development. This data covers percentage changes in quarterly personal consumption expenditure, personal disposable income, production, savings, and the unemployment rate for the US, 1960 to 2016.
