# Medical Insurance Cost Prediction

Estimates medical insurance charges from personal and policyholder features.

## Problem
Predict insurance charges from age, sex, BMI, children, smoking status, and region.

## Dataset
`insurance.csv`; source link: Not specified. The notebook shows 1,338 rows and 7 columns.

## Approach
Encodes the sex, smoker, and region categories as numeric values, then fits Linear Regression on an 80/20 train/test split.

## Results
Linear Regression test R-squared: 0.7447 (notebook output 0.7447273869684076).

## How to run
Run `pip install -r requirements.txt`, then open `Medical_Insurance_Prediction_LinearRegression.ipynb` in Jupyter.

## Tools used
pandas, NumPy, Matplotlib, Seaborn, scikit-learn, and Python `pickle`.
