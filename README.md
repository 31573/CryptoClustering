# CryptoClustering
Introduction
Welcome to the CryptoClustering project! In this project, we aim to use unsupervised learning techniques, specifically K-means clustering, to analyze and cluster cryptocurrencies based on their price changes over time. We will explore how different features and data preprocessing techniques affect the clustering results.

Setup
To get started with the project, follow these steps:

Create a New Repository: Create a new repository on GitHub called CryptoClustering.
Clone the Repository: Clone the newly created repository to your local machine.
Download Files: Download the necessary files for the project from Module 19 Challenge files and place them in the repository folder.
Rename Starter Code: Rename the file Crypto_Clustering_starter_code.ipynb as Crypto_Clustering.ipynb.
Load Data: Load the crypto_market_data.csv file into a DataFrame within your Jupyter Notebook.
Data Preparation
Before diving into clustering, it's essential to prepare the data. Here's what you need to do:

Data Exploration: Get summary statistics and visualize the data to understand its distribution.
Data Normalization: Normalize the data using StandardScaler from scikit-learn.
Feature Indexing: Set the "coin_id" column as the index for the DataFrame.
Clustering with Original Scaled Data
Now, let's cluster the cryptocurrencies using the original scaled data. Follow these steps:

Find Optimal k: Use the elbow method to find the best value for k.
K-means Clustering: Initialize and fit the K-means model using the best k value.
Visualize Clusters: Create a scatter plot to visualize the clusters.
Clustering with PCA Data
Next, we'll perform clustering using Principal Component Analysis (PCA) for dimensionality reduction. Here's what you should do:

PCA: Reduce the features to three principal components.
Find Optimal k: Apply the elbow method on the PCA data to find the best k value.
K-means Clustering: Initialize and fit the K-means model using the best k value.
Visualize Clusters: Create a scatter plot to visualize the clusters based on PCA data.
Conclusion
Finally, compare the clustering results obtained from the original scaled data and PCA data. Consider the impact of using fewer features for clustering and summarize your findings.

Questions to Answer
Throughout the notebook, make sure to answer the following questions:

What is the best value for k when using the original data?
What is the total explained variance of the three principal components obtained from PCA?
What is the best value for k when using the PCA data? Does it differ from the best k value found using the original data?
What is the impact of using fewer features to cluster the data using K-Means?

Chatgbt is used to create readme.
HW completed Tutor's assistance
