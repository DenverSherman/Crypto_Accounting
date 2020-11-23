# Crypto_Accounting
Unsupervised learning and cryptocurrency

## Overview
An Unsupervised Machine Learning Model is implemented over Cryptocurrency data to target future trading. We arrange, execute and visualize the results.

## Data
Data is taken from https://min-api.cryptocompare.com/data/all/coinlist

This is an open API data file that outlines all cryptocurrencies currently being traded. The data is filter for trading and a working algorithm. Null values are dropped. Data is then "dummied" and scaled for use in Principle Component Analysis.

## PCA -> Elbow -> K-Means
A new dataframe is created from our three principle components. From this, we create an elbow curve to find the optimal number of clusters. We then executed the k-means which returns our predicitions.

Predictions are then added to our dataframe as we move towards clustering and visualization.

## Visualization
Our data is later scaled for display in a 3D scatter plot.