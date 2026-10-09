# Spam Message Classification

Classifies text messages as spam or ham using Logistic Regression.

## Problem
Predict whether an incoming message is spam or legitimate.

## Dataset
`mail_data.csv`; source link: Not specified. The notebook shows 5,572 rows and 2 columns.

## Approach
Replaces missing values with empty strings, encodes spam/ham labels, and converts message text to TF-IDF features with English stopword removal. Trains Logistic Regression on an 80/20 split.

## Results
Logistic Regression test accuracy: 0.9668 (notebook output 0.9668161434977578).

## How to run
Run `pip install -r requirements.txt`, then open `Spam_Mail_Predictions_Logistic_Regression.ipynb` in Jupyter.

## Tools used
NumPy, pandas, and scikit-learn.
