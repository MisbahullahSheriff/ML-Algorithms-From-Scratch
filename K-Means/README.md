# K-Means Clustering from Scratch

## Overview:
- This folder contains the code for implementing 2 variants of the K-Means Clustering algorithm
  - K-Means (randomized)
  - K-Means++
- Theese 2 variants have with the same working algorithm, but differ in the way the centroids are initialized
- In the original k-means algorithm, the centroids are initialized randomly
- K-Means++ utilizes a smarter way of initializing centroids

## Files:
- `k_means.ipynb`: contains implementation of the default k-means algorithm
  - This notebook contains code to evaluate the model using the `Elbow Method` with visualizations
- `k_means_pp.ipynb`: contains implementation of k-means++ algorithm
  - This notebook contains code to evaluate the model using `Silhouette Score` with visualizations

## Remarks:
- Due to Random Initialization of centroids, the results will not be reproducible across multiple runs
- With K-Means++, the centroids are initialized in an algorithmic manner rather than randomly
  - It's computationally more expensive than random initialization
  - Often leades to better results
- The efficient time and space complexity of K-Means make it suitable for real-world use-cases
