# Big Mart Sales Prediction

Estimates outlet sales for Big Mart products using product and outlet attributes.

## Problem
Predict item-level sales at retail outlets from product, pricing, and outlet details.

## Dataset
`Train1.csv`; source link: Not specified. The notebook shows 8,523 rows and 12 columns.

## Approach
Fills missing item weights with the mean and missing outlet sizes by outlet-type mode, normalizes fat-content categories, and label-encodes categorical columns. Trains an XGBoost regressor with a train/test split.

## Results
XGBoost test R-squared: 0.5156 (notebook output 0.5155979721907443).

## How to run
Run `pip install -r requirements.txt`, then open `Big_Mart_Sales_Prediction_with_XGB.ipynb` in Jupyter.

## Tools used
NumPy, pandas, Matplotlib, Seaborn, scikit-learn, and XGBoost.
