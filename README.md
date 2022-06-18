# Cryptocurrencies

## Overview

Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. 

Since there is no known output for in crypto dataset (cyrpto_data.csv) unsupervised machine learning is used for this analysis.

## Purpose

The purpose of this analysis is to analyze which cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

## Results
The following steps were executed:

### Preprocessing the Data for PCA
- Filtered by being traded, having a working algorithm
- Removed rows that have at least one null value, 
- Kept rows where coins are mined
### Reducing Data Dimensions Using PCA
- Simplified the list for clustering algorithm, 
- Converted text features to numerical
- Standardized and scaled data, reduced dimensions to 3 principal components
### Clustering Cryptocurrencies Using K-means
- Determined number of clusters through elbow curve
- Determined 4 clusters will be used 
### Visualizing Cryptocurrencies Results
- Used 2D and 3D scatter plots with pca data




