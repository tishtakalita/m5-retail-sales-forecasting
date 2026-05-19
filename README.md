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
  - Zero demand
  - Seasonal demand
- Train-test split: last 28 days used as test set

## Metrics
- MAE
- RMSE

## Status
Baseline modeling completed. Next steps include ML-based forecasting.