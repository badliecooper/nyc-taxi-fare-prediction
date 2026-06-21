# NYC Taxi Fare Prediction

## Overview

This project develops regression models to predict taxi fare amounts using trip characteristics and engineered features.

## Objectives

- Clean and preprocess trip data
- Engineer informative features
- Analyze relationships between variables
- Train regression models
- Compare model performance using evaluation metrics

## Feature Engineering

Created:

- Trip Duration
- One-Hot Encoded RateCodeID

Selected Features:

- Trip Distance
- Trip Duration
- RateCodeID Categories

## Models

1. Linear Regression
2. Decision Tree Regressor

## Evaluation Metrics

- RMSE
- MSE
- MAE
- R² Score

## Key Findings

- Trip distance is the strongest predictor of fare amount.
- Trip duration provides additional predictive information.
- RateCodeID contributes meaningful pricing context.
- Tree-based models capture non-linear fare patterns effectively.

## Tools Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
