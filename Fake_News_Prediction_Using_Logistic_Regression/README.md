# Fake News Classification

Classifies news records as fake or real from author and title text.

## Problem
Predict the fake-news label for a news article record.

## Dataset
`train.csv`; source link: Not specified. The notebook shows 20,800 rows and 5 columns.

## Approach
Fills missing values with empty strings, combines author and title, cleans and stems text, removes English stopwords, and converts text to TF-IDF features. Trains Logistic Regression.

## Results
Logistic Regression test accuracy: 0.9791 (notebook output 0.9790865384615385).

## How to run
Run `pip install -r requirements.txt`, then open `Fake News Prediction_Using_Logistic_Regression.ipynb` in Jupyter.

## Tools used
NumPy, pandas, Python `re`, NLTK, and scikit-learn.
