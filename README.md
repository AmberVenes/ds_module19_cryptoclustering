# ds_module19_cryptoclustering
This challenge applies unsupervised learning to determine how 24-hour and 7-day price changes affect cryptocurrencies. Using StandardScaler, I normalized the data and created a new DataFrame with the scaled values, setting "coin_id" as the index. I then employed PCA to reduce the data to three principal components and re-clustered the cryptocurrencies, visualizing the clusters with scatter plots. The elbow method was used to find the best value for k, providing insights into the clustering behavior of the cryptocurrencies.
