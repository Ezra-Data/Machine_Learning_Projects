# Sonar Rock or Mine Classification

Classifies sonar returns as rock or mine using Logistic Regression.

## Problem
Predict the class label from sonar signal measurements.

## Dataset
`Copy of sonar data.csv`; source link: Not specified. The notebook shows 208 rows and 61 columns: 60 measurements and one label.

## Approach
Separates the 60 numeric measurements from the rock/mine label, then trains Logistic Regression on a stratified 90/10 train/test split.

## Results
Logistic Regression test accuracy: 0.7619 (notebook output 0.7619047619047619).

## How to run
Run `pip install -r requirements.txt`, then open `Sonar Rock Vs Mine Prediction_Logistic_Regression.ipynb` in Jupyter.

## Tools used
NumPy, pandas, and scikit-learn.
