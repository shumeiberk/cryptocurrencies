# Cryptocurrency Challenge

# Objectives
The goals for this challenge are for you to:

Prepare the data for dimensions reduction with PCA and clustering using K-means.
Reduce data dimensions using PCA algorithms from sklearn.
Predict clusters using cryptocurrencies data using the K-means algorithm form sklearn.
Create some plots and data tables to present your results.

# Resources
Data Source: crypto_data.csv Software: Python 3.6.1, Jupyter Notebook 6.0.1, Unsupervised ML


# Challenge Results

A lot of dataprocessing was done to transform the crypto_df original data.  
- After loading the csv, Using python dropna, drop, rename, convert column dtypes the data was transformed so that the misc info that wasn't needed
for the final data output was cleaned up
- Next preprocessing was to use the Standard Scaler to reduce the size of the variables to apply the PCA and Kmeans algorithms
- PCA was used to minimize the data to three principal components for analysis 
- Kmeans was applied to find out optimal clusters needed, best k value = 4
![elbow](https://github.com/shumeiberk/cryptocurrencies/blob/main/images/elbow.PNG)

The results were visualized as follows:

- 3D scatter plots reflects the optimal 4 classes as determined by PCA and Kmeans.  The axes shown is ProofType, TotalCoinsMined,
TotalCoinSupply).  We can see from the clysering where there are similaries 
![Image1](https://github.com/shumeiberk/cryptocurrencies/blob/main/images/Image1.PNG)

- The table below shows that there are 531 observations of crypto that can be traded after filtering out during preprocessing 
![Image2](https://github.com/shumeiberk/cryptocurrencies/blob/main/images/Image2.PNG)

- The final scatter shows where the clusters across the classes of the various crypto options
![Image3](https://github.com/shumeiberk/cryptocurrencies/blob/main/images/Image3.PNG)
