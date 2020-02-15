# Cryptocurrency in an Unsupervised Machine Learning Model
module 18 challenge
## Goals
Analyzing data on hundreds of different kinds of cryptocurrency and using an unsupervised machine learning model to identify clusters of currency with similar characteristics.

## Analysis
Using principal component analysis (PCA) to identify the 3 principle components with the greatest variance. From those variables, we created an elbow curve to identify the optimal number of clusters to create using the Kmeans method. I used KMeans analysis to create 4 clusters within the dataset to plot.

## Findings
The three columns with the most variation are the Algorithm, TotalCoinsMined and TotalCoinSupply. With these components, there are three distinct clusters that are formed. The fourth contains only one cryptocurrency that is an extreme outlier in the TotalCoinSupply column. The remaining 3 columns can be characterized by being either low or high in TotalCoinsMined and low or high in Algorithm. Like this we can cluster the cryptocurrencies in this dataset by these three parameters.
