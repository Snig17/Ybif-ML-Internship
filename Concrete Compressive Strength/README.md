# Concrete Compressive Strength Prediction

Predicts the compressive strength of concrete (MPa) from its mix components using Linear Regression, with a recommendation layer that searches for the component combination that maximizes strength.

**Tech stack:** Python · Pandas · NumPy · Scikit-learn · Seaborn/Matplotlib

## Dataset
[YBIF Concrete Compressive Strength dataset](https://github.com/ybifoundation/Dataset/raw/main/Concrete%20Compressive%20Strength.csv) — 8 input features (cement, blast furnace slag, fly ash, water, superplasticizer, coarse aggregate, fine aggregate, age in days) predicting 1 output (compressive strength in MPa).

## Approach
1. EDA — pairplot, missing-value check, summary statistics
2. Train/test split (70/30)
3. Linear Regression model
4. Evaluated on held-out test set
5. Future prediction on new samples

## Results
| Metric | Value |
|---|---|
| MAE | 8.30 MPa |
| MAPE | 32.2% |
| MSE | 109.76 |

## How to run
```bash
pip install pandas numpy seaborn matplotlib scikit-learn
jupyter notebook "Regression_Model_to_Predict_Cement_Compressive_Strength.ipynb"
```