# Calories Burned Prediction

Estimates calories burned from exercise and body measurements.

## Problem
Predict the calories burned for an exercise record.

## Dataset
`exercise.csv` and `calories.csv`; source link: Not specified. The combined data shown has 15,000 rows and 9 columns.

## Approach
Combines exercise and calorie records, drops User_ID, encodes gender as a numeric feature, and splits data 80/20. Fits an XGBoost regressor.

## Results
XGBoost test mean absolute error: 1.4833678883314132.

## How to run
Run `pip install -r requirements.txt`, then open `Calories_Burnt_Prediction_Using_XGBR.ipynb` in Jupyter.

## Tools used
NumPy, pandas, Matplotlib, Seaborn, scikit-learn, and XGBoost.
