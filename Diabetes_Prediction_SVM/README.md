# Diabetes Prediction

Predicts a diabetes outcome from health measurements using a support vector machine.

## Problem
Classify whether a record has a positive diabetes outcome.

## Dataset
PIMA Diabetes dataset (`diabetes.csv`); source link: Not specified. The notebook shows 768 rows and 9 columns.

## Approach
Standardizes the eight predictor columns, then uses a stratified train/test split and a linear-kernel Support Vector Classifier.

## Results
SVC test accuracy: 0.7727 (notebook output 0.7727272727272727).

## How to run
Run `pip install -r requirements.txt`, then open `Diabetes_Prediction_SVM.ipynb` in Jupyter.

## Tools used
NumPy, pandas, scikit-learn, and Python `pickle`.
