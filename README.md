Cryptocurrency Market Clustering Project

This project performs clustering analysis on cryptocurrency market data to identify groups of similar cryptocurrencies based on their price change percentages over different periods. The project uses K-Means clustering, Principal Component Analysis (PCA), and visualizations to explore and present the clustering results.

Project Structure

-Data Loading and Preparation

-Normalization and Scaling

-Finding Optimal Number of Clusters (Elbow Method)

-K-Means Clustering

-Dimensionality Reduction using PCA

-Cluster Analysis and Visualization

- Data Loading and Preparation

The data is loaded from a CSV file (crypto_market_data.csv) containing the price change percentages of various cryptocurrencies over different time periods.

- Normalization and Scaling

The data is normalized using StandardScaler to ensure that all features contribute equally to the clustering process.

- Finding Optimal Number of Clusters (Elbow Method)

The Elbow Method is used to find the optimal number of clusters (k) by plotting the inertia for different values of k.

- K-Means Clustering

With the optimal number of clusters identified, K-Means clustering is performed.

- Dimensionality Reduction using PCA

PCA is used to reduce the number of features while retaining most of the variance in the data, which helps in visualizing and interpreting the clusters.

- Cluster Analysis and Visualization

The clustering results are visualized using scatter plots and compared between the original and PCA-transformed data.

Conclusion

After performing PCA, the clustering results show that using fewer features (PCA components) can provide clearer, more distinct clusters. Both the original and PCA elbow curves indicate that the optimal number of clusters is 4.
