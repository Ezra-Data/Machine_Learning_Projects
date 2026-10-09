# Credit Card Fraud Detection

Classifies credit card transactions as legitimate or fraudulent.

## Problem
Train a binary classifier on a highly imbalanced transaction dataset.

## Dataset
`credit_data.csv`; source link: Not specified. The notebook shows 284,807 rows and 31 columns.

## Approach
Separates legitimate and fraudulent records, randomly undersamples the majority class to 492 examples, and trains Logistic Regression on a balanced 984-row sample.

## Results
Logistic Regression test accuracy: 0.9289 (notebook output 0.9289340101522843).

## How to run
Run `pip install -r requirements.txt`, then open `Credit_Card_Fraud_Detection_Logistic_Regression.ipynb` in Jupyter.

## Tools used
NumPy, pandas, and scikit-learn.
