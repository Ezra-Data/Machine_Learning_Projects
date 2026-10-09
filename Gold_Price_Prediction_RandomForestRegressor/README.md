# Gold Price Prediction

Estimates gold prices from market indicators using a Random Forest regressor.

## Problem
Predict the GLD target value from other market variables.

## Dataset
`gld_price_data.csv`; source link: Not specified. The notebook shows 2,290 rows and 6 columns.

## Approach
Checks for missing values and explores correlations, then uses SPX, USO, SLV, and EUR/USD as features. Trains a 100-tree Random Forest Regressor with an 80/20 split.

## Results
Random Forest test R-squared: 0.9896 (notebook output 0.9895779248913007).

## How to run
Run `pip install -r requirements.txt`, then open `Gold_Price_Prediction_RandomForestRegressor.ipynb` in Jupyter.

## Tools used
NumPy, pandas, Matplotlib, Seaborn, and scikit-learn.
