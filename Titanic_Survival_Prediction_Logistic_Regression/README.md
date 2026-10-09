# Titanic Survival Prediction

Predicts passenger survival from selected passenger and voyage details.

## Problem
Classify whether a passenger survived.

## Dataset
`train3.csv`; source link: Not specified. The notebook shows 891 rows and 12 columns.

## Approach
Drops the Cabin column, fills missing ages with the mean and missing embarkation ports with the mode, and encodes sex and embarkation port. Removes passenger ID, name, and ticket fields, then trains Logistic Regression on an 80/20 split.

## Results
Logistic Regression test accuracy: 0.7821 (notebook output 0.7821229050279329).

## How to run
Run `pip install -r requirements.txt`, then open `Titanic_Survival_Prediction_Logistic_Regression.ipynb` in Jupyter.

## Tools used
NumPy, pandas, Seaborn, Matplotlib, and scikit-learn.
