# Breast Cancer Classification

Classifies breast tumor records as malignant or benign with logistic regression.

## Problem
Use diagnostic measurements to predict the tumor class.

## Dataset
Scikit-learn's built-in Wisconsin Diagnostic Breast Cancer dataset; source link: Not specified. The notebook shows 569 rows and 30 numeric features.

## Approach
Uses the built-in dataset, separates features from the label, and creates an 80/20 train/test split. Fits a logistic regression classifier.

## Results
Logistic regression test accuracy: 0.9298 (notebook output 0.9298245614035088).

## How to run
Run `pip install -r requirements.txt`, then open `Breast_Cancer_Classification_Prediction_Logistic_Regression.ipynb` in Jupyter.

## Tools used
NumPy, pandas, and scikit-learn.
