# Heart Disease Prediction

Classifies a heart-disease target from clinical measurements using Logistic Regression.

## Problem
Predict the binary heart-disease target from the supplied health features.

## Dataset
`heart_disease_data.csv`; source link: Not specified. The notebook shows 303 rows and 14 columns.

## Approach
Separates the 13 predictor columns from the target and makes a stratified 80/20 train/test split. Fits Logistic Regression.

## Results
Logistic Regression test accuracy: 0.8197 (notebook output 0.819672131147541).

## How to run
Run `pip install -r requirements.txt`, then open `Heart Disease_Prediction_Logistci_Regression.ipynb` in Jupyter.

## Tools used
NumPy, pandas, and scikit-learn.
