# Car Price Prediction

Estimates used-car selling prices from vehicle and ownership details.

## Problem
Predict a used car's selling price from selected numeric and encoded categorical fields.

## Dataset
`Car details v3.csv`; source link: Not specified. The notebook shows 8,128 rows and 13 columns before removing missing rows; 7,906 remain.

## Approach
Drops rows with missing values and encodes fuel, seller type, transmission, and owner. Uses year, kilometers driven, and those encoded fields in a Linear Regression model.

## Results
The notebook reports test R-squared as 0.4776 and test mean absolute error as 315,159.34.

## How to run
Run `pip install -r requirements.txt`, then open `Car_Price_Prediction_Using_Linear_Regression.ipynb` in Jupyter.

## Tools used
pandas, NumPy, Seaborn, Matplotlib, and scikit-learn.
