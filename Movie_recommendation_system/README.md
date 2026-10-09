# Movie Recommendation System

Recommends movies with content similar to a selected title.

## Problem
Find related movies from textual metadata rather than user-rating history.

## Dataset
`movies.csv`; source link: Not specified. The notebook shows 4,803 rows and 24 columns initially; 4,387 rows remain after filtering required fields.

## Approach
Combines genres, keywords, and overview text, removes missing records, cleans and tokenizes text, and removes English stopwords. Builds TF-IDF vectors and ranks titles by cosine similarity.

## Results
For “Batman v Superman: Dawn of Justice,” the notebook recommends Man of Steel, Superman II, Batman Returns, Superhero Movie, and Defendor. No numeric evaluation metric is reported.

## How to run
Run `pip install -r requirements.txt`, then open `Movie_recommendation_system.ipynb` in Jupyter.

## Tools used
NumPy, pandas, Matplotlib, scikit-learn, WordCloud, NLTK, and Python `re`.
