# Customer Segmentation

Groups mall customers by annual income and spending score.

## Problem
Discover customer segments from income and spending behavior without labeled outcomes.

## Dataset
`Mall_Customers.csv`; source link: Not specified. The notebook shows 200 rows and 5 columns.

## Approach
Selects annual income and spending score as clustering features, uses the elbow method on within-cluster sum of squares, then fits K-means with five clusters and plots the assignments and centroids.

## Results
The notebook selects five clusters from the elbow plot; it reports no numeric evaluation metric.

## How to run
Run `pip install -r requirements.txt`, then open `Customer_Segmentation_Kmeans.ipynb` in Jupyter.

## Tools used
NumPy, pandas, Matplotlib, Seaborn, and scikit-learn.
