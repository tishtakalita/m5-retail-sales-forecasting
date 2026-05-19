# M5 Retail Sales Forecasting

## Overview
This project implements baseline forecasting models using selected time series from the M5 dataset.

## Models Implemented
Baseline models:
- Naive Forecast
- Seasonal Naive Forecast
- Moving Average (Simple and Recursive)
- ETS (Error, Trend, Seasonal)
- ARIMA

## Data
Data is not included in this repository. The M5 competition dataset can be downloaded from [Kaggle](https://www.kaggle.com/competitions/m5-forecasting-accuracy/data).

## Methodology
- 3 representative time series selected:
  - Stable demand
  - Sporadic demand
  - Seasonal demand
- Training data: `sales_train_validation` (d_1 to d_1913)
- Testing data: `sales_train_evaluation` (d_1914 to d_1941), the last 28 days

## Metrics
- MAE
- RMSE

## Status
Baseline modeling completed. Next steps include ML-based forecasting.