# CryptoClustering

 Unsupervised learning is used to predict if cryptocurrencies are affected by 24 hour or 7 day price changes. 

First the data is normalized using the StandardScaler() module. Then a dataframe is generated and the best value for k is found. Next, a dictionary is created in order to plot the elbow curve. I found that the best value for 'k' is 4. Next, I defined, fit, and predicted the model. A scatter plot was created using hvPlot setting the "coin_id" column as the hover_cols parameter to identify the cryptocurrency represented by each data point.

Then, I optimized the clusters with a Principal Component analysis. Using the original scaled DataFrame, I performed a PCA and reduced the features to three principal components. Then the best value for 'k' is found using the PCA data as well as a new cluster plot.
