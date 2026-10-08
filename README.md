# Polynomial Regression – BT2024209

Predicting y for two datasets (var1: 6 features, var2: 3 features) using polynomial regression with regularization.

## Final models
- var1: degree-5 polynomial, standardized, Lasso (alpha = 0.015)
- var2: degree-12 polynomial, standardized, Ridge (alpha = 2)

## Files
- `BT2024209_polynomial_regression.ipynb` – all code: EDA, validation, degree/alpha searches, final fits, predictions
- `BT2024209_pred_var1.csv`, `BT2024209_pred_var2.csv` – test predictions
- `BT2024209_report.pdf` – write-up

## How to run
Open the notebook in Google Colab. Cell 1 asks you to upload the 4 data files:
BT2024209_train_var1.csv, BT2024209_test_var1.csv, BT2024209_train_var2.csv, BT2024209_test_var2.csv.
Then run all cells in order. Requires numpy, pandas, scikit-learn, matplotlib.
