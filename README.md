🌧️ Andhra Pradesh Rainfall Forecasting (Coastal AP + Rayalaseema)

This project builds a high-accuracy annual rainfall forecasting model for the Andhra Pradesh region (specifically Coastal Andhra Pradesh + Rayalaseema).
It uses advanced feature engineering, time-series ML models, and a weighted ensemble to achieve strong predictive performance.

The model forecasts future rainfall for the years 2018 to 2028.
Key Features
🔹 1. Ensemble Machine Learning Model

A weighted combination of:

Gradient Boosting Regressor (GBR) – primary learner

Random Forest Regressor (RF) – stabilizes variance

Ridge Regression – helps capture linear trend
🔹 2. Time-Based Train–Test Split

To avoid data leakage:

80% of earliest years → training

20% of latest years → testing

This mimics real-world forecasting conditions.
🔹 3. High Model Performance (Achieved)

The ensemble achieves:

Metric	Score
RMSE	~ 76.38
MAE	~ 55.12
R²	~ 0.878

This is exceptionally strong for long-range rainfall prediction.
