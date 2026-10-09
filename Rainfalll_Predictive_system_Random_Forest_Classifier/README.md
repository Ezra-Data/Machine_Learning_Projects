# Rainfall Prediction

Predicts whether rainfall will occur from daily weather measurements.

## Problem
Classify rainfall occurrence using recorded weather conditions.

## Dataset
`Rainfall.csv`; source link: Not specified. The notebook shows 366 rows and 12 columns.

## Approach
Removes the day field, fills missing weather values, maps rainfall labels to binary values, and balances the classes by resampling. Tunes a Random Forest classifier with grid search and five-fold cross-validation.

## Results
Tuned Random Forest test accuracy: 0.8298 (notebook output 0.8297872340425532).

## How to run
Run `pip install -r requirements.txt`, then open `Rainfalll_Predictive system_Random_Forest_Classifier.ipynb` in Jupyter.

## Tools used
NumPy, pandas, Matplotlib, Seaborn, scikit-learn, and Python `pickle`.
