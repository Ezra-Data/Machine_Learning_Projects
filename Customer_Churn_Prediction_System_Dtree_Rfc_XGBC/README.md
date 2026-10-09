# Customer Churn Prediction

Predicts whether a telecom customer is likely to leave the service.

## Problem
Classify customer churn from account, service, contract, and billing information.

## Dataset
Telco Customer Churn (`WA_Fn-UseC_-Telco-Customer-Churn.csv`); source link: Not specified. The notebook shows 7,043 rows and 21 columns.

## Approach
Drops the customer ID, replaces blank total charges with zero, converts charges to numeric, and label-encodes categorical fields. Balances training data with SMOTE and compares Decision Tree, Random Forest, and XGBoost classifiers using five-fold cross-validation.

## Results
Random Forest has the highest reported cross-validation accuracy (0.84). The evaluation cell reports test accuracy of 0.7793.

## How to run
Run `pip install -r requirements.txt`, then open `Customer_Churn_Prediction_System_Dtree_Rfc_XGBC.ipynb` in Jupyter.

## Tools used
NumPy, pandas, Matplotlib, Seaborn, scikit-learn, imbalanced-learn, XGBoost, and Python `pickle`.
