# Song Recommendation System

Recommends songs with lyrics similar to a selected song.

## Problem
Find related songs using lyric content rather than listening history.

## Dataset
Spotify Million Song Dataset, `spotify_millsongdata.csv`; [Kaggle dataset](https://www.kaggle.com/datasets/notshrirang/spotify-million-song-dataset/data). The notebook shows 57,650 rows and 4 columns, then samples 10,000 rows.

## Approach
Cleans lyrics, removes English stopwords, and builds TF-IDF vectors from a 10,000-row sample. Uses cosine similarity to return the five nearest songs.

## Results
The recommendation function returns five song suggestions; the notebook reports no numeric evaluation metric.

## How to run
Run `pip install -r requirements.txt`, then open `Music_Recommendation_System_using_Python_code_prep_2.ipynb` in Jupyter. The notebook uses Kaggle API authentication to download the dataset.

## Tools used
NumPy, pandas, Matplotlib, scikit-learn, WordCloud, NLTK, Python `os`, `json`, `zipfile`, `getpass`, and `re`.
