# Cryptocurrency Clustering

## Data Preparation
Read crypto_data.csv into Pandas. The dataset was obtained from CryptoCompare.

Discard all cryptocurrencies that are not being traded. 

Remove all rows that have at least one null value.

Filter for cryptocurrencies that have been mined.

Delete the CoinName from the original dataframe.

Convert the remaining features with text values, Algorithm and ProofType, into numerical data.

Standardize your dataset so that columns that contain larger values do not unduly influence the outcome.

## Dimensionality Reduction

Creating dummy variables above dramatically increased the number of features in your dataset. Perform dimensionality reduction with PCA. For this assignment, preserve 90% of the explained variance in dimensionality reduction.

Next, further reduce the dataset dimensions with t-SNE and visually inspect the results. 

## Cluster Analysis with k-Means

Create an elbow plot to identify the best number of clusters. Use a for-loop to determine the inertia for each k between 1 through 10. Determine, if possible, where the elbow of the plot is, and at which value of k it appears.
