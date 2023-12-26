# Principal Component Analysis from Scratch

## Overview:
- This folder contains the code for implementing the PCA algorithm
- This project implements PCA using `Eigen Decomposition`
 
## Files:
- `pca.ipynb`: contains implementation of PCA using eigen decomposition

## Remarks:
- PCA is an `Unsupervised` algorithm primarily used for performing `Dimensionality Reduction`
- It helps avoid the `Curse of Dimensionality` through `Dimensionality Reduction`
- It involves performing `Feature Extraction`, i.e., it combines the existing features in the dataset to generate completely new features altogether
- PCA mainly aims to retain maximum variance present in the original dataset
- PCA finds a smaller feature space wherein the dataset can be projected onto, such that the inevitable loss of information is minimal
- The principal components are all orthogonal to each other, therefore, the derived features will be uncorrelated to each other
- PCA is can be used as a preprocessing step while training predictive models to:
  - Avoid overfitting
  - Speed up model training
  - Sometimes provide better predictive performance
- PCA works well on linear datasets
- When dealing with complex, manifold and non-linear datasets it may be better to use techniques like:
  - `t-distributed Stochastic Neighbour Embedding (t-SNE)`
  - `Locally Linear Embedding (LLE)`
