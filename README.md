# crypto clustering

# Crypto Clustering

In this challenge we are tasked with the analysis of crypto stock data to select the best components for use with predictions. It will show an understanding and use of K-Means and Principal Component Analysis (PCA)

## Workflow
1. Prepare original data by reading it into a pandas data frame and setting the index to the "coin_id"
    - This includes scaling the data using StandardScalar to fit the data.
2. Find the K-Means of the scaled data
    - Fit, predict and graph the results
3. Optimize the data with PCA and find the K-Means
    - Fit the PCA reduced data, predict and graph the results.
4. Find the weights of the PCA scaled components.