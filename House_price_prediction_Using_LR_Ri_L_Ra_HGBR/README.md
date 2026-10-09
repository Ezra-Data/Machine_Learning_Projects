# House Price Prediction

Predicts median house values from housing-block attributes and proximity to the ocean.

## Problem
Estimate `median_house_value` using numeric measurements and a categorical location feature.

## Dataset
`housing.csv`; source link: Not specified. The notebook shows 20,640 rows and 10 columns.

## Approach
Imputes numeric missing values with medians, imputes categorical values with the mode, scales numeric columns, and one-hot encodes categories in a pipeline. Compares Linear Regression, Ridge, Lasso, Random Forest, and HistGradientBoosting; tunes HistGradientBoosting with grid search.

## Results
Tuned HistGradientBoosting test RMSE: 46,721.710; MAE: 30,854.241; R-squared: 0.833.

## How to run
Run `pip install -r requirements.txt`, then open `House_price_prediction_Using_LR_Ri_L_Ra_HGBR.ipynb` in Jupyter.

## Tools used
NumPy, pandas, Matplotlib, Seaborn, and scikit-learn.
