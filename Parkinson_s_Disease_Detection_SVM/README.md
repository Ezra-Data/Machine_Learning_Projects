# Parkinson's Disease Detection

Classifies voice-measurement records for Parkinson's disease status.

## Problem
Predict the status label from biomedical voice measurements.

## Dataset
`parkinsons (1).csv`; source link: Not specified. The notebook shows 195 rows and 24 columns.

## Approach
Drops the name field, separates 22 numeric predictors from the status label, and standardizes features using training-set statistics. Trains a linear-kernel Support Vector Classifier.

## Results
SVC test accuracy: 0.8718 (notebook output 0.8717948717948718).

## How to run
Run `pip install -r requirements.txt`, then open `Parkinson_s Disease_Detection_SVM.ipynb` in Jupyter.

## Tools used
NumPy, pandas, and scikit-learn.
