# logistic-regression-breast-cancer
"Binary classification using Logistic Regression on Breast Cancer Dataset"
# Logistic Regression - Breast Cancer Classification

This project applies a Logistic Regression model to classify tumors as benign or malignant using the Breast Cancer Wisconsin Dataset.

## Contents
- `logistic_regression.py`: Python script with the full code.
- `data.csv`: Breast Cancer dataset (UCI format).
- `screenshots/`: Optional folder with screenshots or graphs.
- `README.md`: This documentation.

## Steps
1. Loaded dataset from CSV.
2. Preprocessed data (removed constant columns, handled missing values).
3. Applied `StandardScaler`.
4. Trained a `LogisticRegression` model using Scikit-learn.
5. Evaluated using confusion matrix, classification report, ROC-AUC.
6. Tuned classification threshold and plotted ROC Curve.

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn
