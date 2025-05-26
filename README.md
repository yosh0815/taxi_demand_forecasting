# Time Series Forecasting of Taxi Demand

This project forecasts hourly taxi demand using historical ride data. The goal is to improve fleet planning and pricing strategy by predicting ride volume in advance. The project applies classic time series modeling techniques like ARIMA to generate accurate short-term forecasts.

## Overview

- **Goal:** Forecast number of taxi rides per hour using time series data
- **Model:** Seasonal ARIMA (SARIMA), baseline linear models
- **Dataset:** NYC taxi rides, resampled and aggregated by hour
- **Result:** Captured temporal trends, seasonality, and peaks to guide decision-making
- **Business Impact:** Helps reduce driver downtime and optimize supply during peak hours

## Tools & Libraries

- Python
- Pandas, NumPy
- Statsmodels (ARIMA)
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## Project Structure

```bash
taxi_demand_forecasting/
├── taxi_forecast_arima.ipynb     # Main notebook with forecasting workflow
├── requirements.txt              # Python dependencies
├── data/                         # (Optional) Sample CSVs or resampled ride data
├── images/                       # Forecast plots
└── README.md                     # Project summary
