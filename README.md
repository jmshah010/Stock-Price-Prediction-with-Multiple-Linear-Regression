# Stock-Price-Prediction-with-Multiple-Linear-Regression
Forecasts AU Bank stock closing prices using linear regression in Python, with VIF analysis and feature importance plots.


# Notes
Dataset: Replace 'au-bank.csv' with the path to your dataset.

Outputs: Plots are saved as actual_vs_predicted.png and feature_importance.png.

Multicollinearity: The final feature set (open, 52w_high, 52w_low, volume, no_of_trades, day_of_week, month) was selected to minimize high VIF values.

Performance: The model achieves an R² score of ~0.993, indicating strong predictive power, though high VIF for some features suggests potential multicollinearity.
