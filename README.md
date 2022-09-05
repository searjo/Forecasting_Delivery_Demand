# Forecasting_Delivery_Demand
Demand forecasting with synthetic food delivery data

The results indicate a few key takeaways:

The naive model (just predicting this week based on last week) worked very well and held up to the RF and XGBoost algorithms, and actually performed best according to the SMAPE evaluation metric.

Multiple evaluation metrics are important - the MSE moving averages indicate that XGBoost performed best, while the SMAPE moving averages indicate that XGboost performed worst.

A gridsearch and hyperparameters tuning would be best practice if continuing this project. Further tuning and experimentation would likely improve the XGB and RF models.
