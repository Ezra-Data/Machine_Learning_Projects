# Loan Status Prediction

Predicts loan approval status from applicant information using a support vector machine.

## Problem
Classify loan applications as approved or not approved.

## Dataset
`Dataset.csv`; source link: Not specified. The notebook shows 614 rows and 13 columns before dropping incomplete records; 480 remain.

## Approach
Drops rows with missing values, encodes categorical fields and loan status, and maps `3+` dependents to 4. Trains a linear-kernel Support Vector Classifier on an 90/10 stratified split.

## Results
SVC test accuracy: 0.8333 (notebook output 0.8333333333333334).

## How to run
Run `pip install -r requirements.txt`, then open `Loan_Statues_prediction_SVM.ipynb` in Jupyter.

## Tools used
NumPy, pandas, Seaborn, and scikit-learn.
