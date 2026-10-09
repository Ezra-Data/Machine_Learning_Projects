# Autism Classification

Predicts an autism screening class from questionnaire and demographic features.

## Problem
Classify whether a record has the positive autism-screening label.

## Dataset
`train.csv`; source link: Not specified. The notebook shows 800 rows and 22 columns.

## Approach
Drops ID and age-description fields, normalizes missing categorical values, label-encodes categories, replaces age/result outliers with medians, and applies SMOTE. Compares Decision Tree, Random Forest, and XGBoost classifiers with randomized search and cross-validation.

## Results
Random Forest had the best cross-validation accuracy (0.92); test accuracy was 0.825.

## How to run
Run `pip install -r requirements.txt`, then open `Autism_Prediction_Using_Dtree_Rfc_XGB.ipynb` in Jupyter.

## Tools used
NumPy, pandas, Matplotlib, Seaborn, scikit-learn, imbalanced-learn, XGBoost, and Python `pickle`.
