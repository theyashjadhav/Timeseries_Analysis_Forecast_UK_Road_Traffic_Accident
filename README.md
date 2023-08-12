# UK Road Traffic and Accident Analysis

This project involves an in-depth analysis of United Kingdom road traffic and accident data, spanning from 2005 to 2017 for accidents. The main focus is on descriptive analysis, data visualization, and forecasting. The goal is to predict the accident rate for the next two years using available time series data.

### Time Series Forecasting of Road Accidents

- Forecasting road accident casualties for the next 2 years.
- Experimenting with different Long-Short Term Memory (LSTM) models.
- Utilizing SARIMA and Facebook Prophet models for accurate forecasts.

## Python Libraries Used

- Pandas
- Numpy
- Sci-kit learn
- Statsmodels
- Pmdarima
- Plotly
- GeoPandas
- Keras
- Facebook Prophet
- Matplotlib



## Time Series Forecasting Results

### Model Training Results (Jan 2005 - Dec 2013)

| Models             | MAE   | MAPE   |
| ------------------ | ----- | ------ |
| LSTM               | 30.53 | 6.82   |
| GRU                | 30.02 | 6.70   |
| Convolutional LSTM | 20.98 | 4.10   |

-  Convolutional LSTM emerges as the top-performing model for time series forecasting.
- LSTM models faced challenges with generalization due to limited data.



