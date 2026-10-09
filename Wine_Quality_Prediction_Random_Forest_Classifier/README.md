# Red Wine Quality Classification

Classifies red wine as good or lower quality from physicochemical measurements.

## Problem
Predict whether a wine's quality score is at least 7.

## Dataset
`winequality-red.csv`; source link: Not specified. The notebook shows 1,599 rows and 12 columns.

## Approach
Uses the 11 physicochemical measurements as features and binarizes quality as 1 for scores of 7 or higher, otherwise 0. Trains a Random Forest classifier with an 80/20 split.

## Results
Random Forest test accuracy: 0.925.

## How to run
Run `pip install -r requirements.txt`, then open `Wine_Quality_Prediction_Random_Forest_Classifier.ipynb` in Jupyter.

## Tools used
NumPy, pandas, Matplotlib, Seaborn, and scikit-learn.
