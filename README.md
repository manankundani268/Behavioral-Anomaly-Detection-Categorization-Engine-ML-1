# Behavioral-Anomaly-Detection-Categorization-Engine-ML-1
Credit Card Fraud Detection:

This is a machine learning project I worked on to detect fraudulent credit card transactions. The main issue with this dataset is extreme class imbalance—fraud cases are super rare (around 0.3%), so a regular model just tries to predict everything as normal and fails completely.

What I did in the notebook:
- Handled missing values and scaled the features using scikit-learn.
- Tuned the XGBoost hyperparameters using RandomizedSearchCV.
- Wrote a custom threshold loop instead of using the default 0.5 cutoff to maximize the F1-score and catch actual fraud.
- Saved the final model, scaler, and imputer using joblib.

Files included:
- The Colab notebook
- xgboost_tuned_fraud_model.pkl
- scaler.pkl
- imputer.pkl
- requirements.txt
