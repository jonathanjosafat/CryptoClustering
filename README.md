# CryptoClustering
 
- This project uses unsupervised learning techniques, specifically K-means clustering, to analyze cryptocurrencies and determine how they are affected by 24-hour and 7-day price changes. The goal is to understand the clustering behavior of cryptocurrencies by leveraging PCA (Principal Component Analysis) to reduce dimensionality and improve clustering accuracy.

- In this project, we use clustering techniques to predict how cryptocurrencies are affected by their 24-hour and 7-day price changes. The dataset consists of various cryptocurrency data, which we preprocess, normalize, and reduce to key principal components for clustering.

- Key steps in the project:

1. Load and preprocess the cryptocurrency data.
2. Use K-means clustering to group cryptocurrencies based on their price change percentages.
3. Apply PCA to reduce the data to three principal components and perform clustering again.
4. Use the elbow method to identify the optimal number of clusters.
5. Visualize the clustering results and assess the impact of dimensionality reduction on clustering performance.