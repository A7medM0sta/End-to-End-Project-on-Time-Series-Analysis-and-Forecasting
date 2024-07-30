# Time Series Analysis and Forecasting

This project involves analyzing and forecasting furniture sales data using time series techniques.

## Project Steps

1. **Data Preprocessing**: The data is cleaned and preprocessed. This involves renaming columns, handling missing values, and converting the data into a time series format.

2. **Exploratory Data Analysis**: The data is visualized to understand the underlying patterns such as trends and seasonality.

3. **Time Series Decomposition**: The time series data is decomposed into trend, seasonality, and residuals.

4. **Model Building**: The ARIMA model is used for forecasting. The model parameters are selected based on the AIC criterion.

5. **Model Diagnostics**: The residuals of the model are checked to ensure that the model assumptions are met.

6. **Forecasting**: The model is used to forecast future furniture sales.

## Code

The project is implemented in Python using libraries such as pandas, numpy, matplotlib, statsmodels, and plotly.

## Results

The model was able to capture the trend and seasonality in the furniture sales data, resulting in a good fit to the observed data. The one-step ahead forecast also aligns well with the actual sales.

## Future Work

This project can be extended by trying out different models, tuning the model parameters, or using a larger dataset for more accurate forecasts.
