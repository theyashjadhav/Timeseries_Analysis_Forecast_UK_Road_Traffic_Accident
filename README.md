# UK Road Traffic and Accident Analysis

This project involves an in-depth analysis of United Kingdom road traffic and accident data, spanning from 2005 to 2017 for accidents. The main focus is on descriptive analysis, data visualization, and forecasting. The goal is to predict the accident rate for the next two years using available time series data.

### Time Series Forecasting of Road Accidents
Notebook: [TimeSeries Forecast](https://nbviewer.jupyter.org/github/AdeboyeML/Predictive_Analytics_UK_Road_Traffic_Accident/blob/master/UK_Road_Accident_Timeseries_Forecasting.ipynb)

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

![UK Road Traffic](./uk_region.png)

## Analytics and Visualization Highlights

![Vehicle Trends](./analytics_viz/veh_trend.png)
![Road Categories](./analytics_viz/rd_cat.png)
![Geographical Regions](./analytics_viz/reg_trd.png)
![Accident Trends](./analytics_viz/reg_acc.png)
![Road Network](./analytics_viz/rd_net.png)
![Accident Trends](./analytics_viz/acc_trd.JPG)
![Traffic Flow](./analytics_viz/hr_flow.JPG)

## Time Series Forecasting Results

### Model Training Results (Jan 2005 - Dec 2013)

| Models             | MAE   | MAPE   |
| ------------------ | ----- | ------ |
| LSTM               | 30.53 | 6.82   |
| GRU                | 30.02 | 6.70   |
| Convolutional LSTM | 20.98 | 4.10   |

- Facebook Prophet emerges as the top-performing model for time series forecasting.
- LSTM models faced challenges with generalization due to limited data.
- Only SARIMA and Facebook Prophet are used for the final 2-year accident rate forecast.

## Time Series Forecast

### SARIMA (Seasonal - Autoregressive Integrated Moving Average) Model
![SARIMA Forecast](./analytics_viz/sar_fr.JPG)

### Facebook Prophet Model
![Facebook Prophet Forecast](./analytics_viz/fb_forecast.JPG)
