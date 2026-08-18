# Multiple Disease Classification

Classifies disease (prognosis) from a set of symptoms using a Random Forest Classifier.

**Tech stack:** Python · Pandas · NumPy · Scikit-learn · Seaborn/Matplotlib

## Dataset
[YBIF Multiple Disease Prediction dataset](https://github.com/ybifoundation/Dataset/raw/main/MultipleDiseasePrediction.csv) — binary symptom indicators predicting a disease label (prognosis).

## Approach
1. EDA — correlation heatmap, missing-value check
2. Train/test split
3. Random Forest Classifier
4. Evaluated with accuracy, confusion matrix, classification report

## Results
| Metric | Value |
|---|---|
| Accuracy | 100% |

*Note: this dataset is highly separable by symptom pattern, which is why accuracy is near-perfect — not a claim of a hard problem solved.*

## How to run
```bash
pip install pandas numpy seaborn matplotlib scikit-learn
jupyter notebook Classification_Model_to_Identify_Multiple_Disease.ipynb
```