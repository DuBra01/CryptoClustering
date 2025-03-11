# CryptoClustering
 Overview

This project applies K-Means Clustering to analyze cryptocurrency market data. It demonstrates how clustering can be optimized using Principal Component Analysis (PCA) to reduce feature dimensions while preserving clustering performance.

Dataset

The dataset contains various percentage price changes for different cryptocurrencies over multiple timeframes.

Features include 24-hour, 7-day, 14-day, 30-day, and yearly price change percentages.

Methods

K-Means Clustering (Original Data):

Standardized the dataset using StandardScaler().

Applied Elbow Method to determine the optimal number of clusters.

Created scatter plots to visualize clustering results.

K-Means Clustering (PCA-Optimized Data):

Reduced dimensions to 3 Principal Components using PCA.

Re-applied K-Means Clustering and compared results with the original dataset.

Key Findings

The Elbow Method identified 4 clusters as the optimal choice.

PCA improved efficiency without significantly affecting cluster separation.

Clustering results were similar in both original and PCA-transformed datasets, validating that fewer features retained meaningful patterns.

Visualization

Elbow Curves (Before & After PCA) were plotted to compare inertia values.

Scatter Plots were used to display cluster separations.

Different markers and colors were applied to differentiate clusters.

Technologies Used

Google Colab

Python (Pandas, Sklearn, hvPlot, Matplotlib, PCA)

K-Means Clustering & Principal Component Analysis (PCA)

How to Use

Open the .ipynb file in Google Colab.

Run each cell sequentially to replicate the clustering process.

Modify parameters such as n_components (PCA) or n_clusters (K-Means) for experimentation.
