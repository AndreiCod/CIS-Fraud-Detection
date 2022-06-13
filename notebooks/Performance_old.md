# Peformance of algorithms using AUC metric

| Algorithm | Added Feature | Performance | Time | Fraud Transaction multiplier in train |
| --------- | ------------- | ----------- | ---- | ------------------------------------- |
| XGBoost | None | 0.9234840868118391 | 4m 30.1s | 1 |
| Logistic Regression | None | 0.7804893356086602 | 1m 15.9s | 1 |
| XGBoost | Removed missing cols | 0.9233120753966862 | 4m 20.2s | 1 |
| XGBoost | Added time features | 0.9230010571878804 | 4m 15.1s | 1 |
| XGBoost | Removed correlated features | 0.9228320990303722 | 3m 3.3s | 1 |
| XGBoost | Removed TransactionAmt outlier | 0.9244926234148201 | 3m 10.8s | 1 |
| XGBoost | Added uid | 0.9254216274365361 | 3m 17.4s | 1 |
| XGBoost | Balanced dataset | 0.9158468466981278 | 3m 15.1s | 10 |