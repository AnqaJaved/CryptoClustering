# Crypto Clustering - Module 19 Challenge

This notebook uses unsupervised machine learning techniques to group cryptocurrencies based on their price change behaviors. Both K-Means clustering and Principal Component Analysis (PCA) were applied.

## Key Steps:
- Normalized market data using StandardScaler
- Found optimal `k` using the elbow method
- Clustered coins using KMeans on both raw and PCA-reduced data
- Visualized clusters and elbow curves using hvPlot

## Final Result:
The best number of clusters was found to be 4 in both cases. PCA helped simplify the dataset while preserving around 89.5% of the data’s variance.

📁 Notebook: `Crypto_Clustering.ipynb`
