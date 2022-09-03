# Forecasting_Delivery_Demand
Demand forecasting with food delivery data for Intelligent Data Design at Barcelona School of Economics.

The results indicate a few key takeaways:

The naive model (just predicting this week based on last week) worked very well and held up to the RF and XGBoost algorithms, and actually performed best according to the SMAPE evaluation metric.

Multiple evaluation metrics are important - the MSE moving averages indicate that XGBoost performed best, while the SMAPE moving averages indicate that XGboost performed worst.

Finally - we recognize a gridsearch and hyperparameters tuning would be best practice here, however we believe it is outside the scope of this assignment. Further tuning and experimentation would likely improve the XGB and RF models.
