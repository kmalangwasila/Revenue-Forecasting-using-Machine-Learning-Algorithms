Revenue Forecasting in a Tax Administration — End-to-End
Objective: Build a reproducible revenue forecasting pipeline using monthly revenue data (5 years), feature engineering, statistical tests, and six machine learning algorithms. This notebook is designed for classroom use — each step contains code and explanatory notes so students can follow along and adapt to real tax data.


Simulating or loading monthly revenue + macro / compliance drivers
Exploratory Data Analysis (EDA)
Data cleaning and transformations
Feature engineering for time series (lags, rolling stats, seasonality)
Statistical feature selection (OLS p-values)
Training and cross-validating multiple ML models (time-series CV)
Hold-out evaluation and model selection (RMSE, MAPE, R²)
Recursive multi-step forecasting with the best model
Practical notes on productionising the model
Prerequisites: Python packages: pandas, numpy, matplotlib, scikit-learn, statsmodels, joblib, nbformat.
