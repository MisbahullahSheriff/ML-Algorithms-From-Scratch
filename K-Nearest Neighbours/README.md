# K-Nearest Neighbours from Scratch

## Overview:
- This folder contains the code for implementing the KNN algorithm for both, Regression and Classification

## Files:
- `knn_classifier.ipynb`: contains implementation of knn classificatier
- `knn_regressor.ipynb`: contains implementation of knn regressor

## Remarks:
- KNN is a versatile algorithm
- It can be used for performing Regression as well as Classification
- KNN is an `instance-based` method:
  - It doesn't learn any parameters
  - Doesn't involve mathematical optimization
- Its often also called as a `lazy learning` algorithm
- The time and space complexity is very high in the case of KNN:
  - It stores the training data in memory
  - Goes through the entire training data for each query point during prediction
