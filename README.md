# NVIDIA Stock Analysis Project

## Overview
This project focuses on analyzing NVIDIA's stock performance using various machine learning models and statistical techniques. The goal is to predict stock prices and generate trading signals to optimize investment strategies.

## Table of Contents

1. **NVIDIA Stock Analysis**
    - Historical data analysis of NVIDIA stock including open, high, close, and low prices.
2. **NVIDIA and Competitors Comparison & Analysis**
    - Comparative analysis with NVIDIA's competitors.
    - Report summary statistics and kernel density plots for the training period.
3. **Feature Engineering**
    - Feature engineering techniques applied to enhance model performance.
4. **Machine Learning Models**
    - Implemented machine learning models:
        - Ridge Regression
        - Lasso Regression
        - Elastic Net Regression
        - Random Forest
        - XGBoost
        - Linear Regression
        - Gradient Boosting
5. **Time Series Models**
    - SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous factors)
    - GARCH (Generalized Autoregressive Conditional Heteroskedasticity)
6. **Trading Rules**
    - Composed trading rules including buy-and-hold, long-short, and day trading strategies.
7. **Generating Trading Signals**
    - Utilized machine learning and time series models to generate trading signals.
8. **Performance Evaluation**
    - Compared Profit and Loss (PnL) of different models to assess their effectiveness in trading strategies.

## Usage
1. **Data Preparation**
    - Ensure NVIDIA stock data and competitor data is available.
2. **Feature Engineering**
    - Execute feature engineering scripts to preprocess data.
3. **Model Training**
    - Train machine learning and time series models on prepared data.
4. **Signal Generation**
    - Generate trading signals using trained models.
5. **Performance Evaluation**
    - Evaluate model performance by comparing PnL across different strategies.

## Dependencies
- Python 3.x
- Libraries: pandas, numpy, scikit-learn, statsmodels, xgboost, matplotlib, seaborn
