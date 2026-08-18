# Employee Attrition Classification

Predicts whether an employee will leave the company using a Random Forest Classifier on HR data.

**Tech stack:** Python · Pandas · NumPy · Scikit-learn · Seaborn/Matplotlib

## Dataset
[YBIF Employee Attrition dataset](https://github.com/ybifoundation/Dataset/raw/main/EmployeeAttrition.csv) — HR features (age, income, job satisfaction, distance from home, etc.) predicting attrition (Yes/No).

## Approach
1. EDA — correlation matrix, pairplot, missing-value check
2. Train/test split (70/30)
3. Random Forest Classifier
4. Evaluated with accuracy, confusion matrix, classification report

## Results
| Metric | Value |
|---|---|
| Accuracy | 86.2% |
| Precision (Attrition = Yes) | 0.71 |
| Recall (Attrition = Yes) | 0.15 |

## How to run
```bash
pip install pandas numpy seaborn matplotlib scikit-learn
jupyter notebook Classification_Model_to_Identify_Employee_Attrition.ipynb
```