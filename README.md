# M5 Retail Sales Forecasting

## Overview
This project implements forecasting models on the M5 Walmart dataset, progressing from baseline statistical models to ML-based forecasting.

## Models Implemented
Baseline models:
- Naive Forecast
- Seasonal Naive Forecast
- Moving Average (Simple and Recursive)
- ETS (Error, Trend, Seasonal)
- ARIMA

ML models (in progress):
- LightGBM

## Data
Data is not included in this repository. The M5 competition dataset can be downloaded from [Kaggle](https://www.kaggle.com/competitions/m5-forecasting-accuracy/data).

## Methodology
- Training data: `sales_train_validation` (d_1 to d_1913)
- Testing data: `sales_train_evaluation` (d_1914 to d_1941), the last 28 days
- Baseline: 3 representative time series selected:
  - Stable demand
  - Sporadic demand
  - Seasonal demand
- ML piepline: full 30,490 item-store combinations with feature engineering

## Notebooks
- `01_baseline_models.ipynb` — statistical baseline models
- `02_data_preprocessing.ipynb` — data cleaning, merging, encoding

## Metrics
- MAE
- RMSE

## Status
Baseline modeling completed. Data preprocessing pipeline completed. Feature engineering in progress.