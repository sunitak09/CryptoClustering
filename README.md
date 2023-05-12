# CryptoClustering To predict if cryptocurrencies are affected by 24-hour or 7-day price changes

**Data Preparation**
Use the StandardScaler() module from scikit-learn to normalize the data from the CSV file.
Create a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.


**Visualizations and Analysis**

Find the Best Value for k Using the Original Scaled DataFrame.

Cluster Cryptocurrencies with K-means Using the Original Scaled Data.

Optimize Clusters with Principal Component Analysis.

Find the Best Value for k Using the PCA Data.

Cluster Cryptocurrencies with K-means Using the PCA Data.
