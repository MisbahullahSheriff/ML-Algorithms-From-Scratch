# Linear Regression from Scratch

## Overview:
- This folder contains the code for implementing 2 variants of the Linear Regression algorithm:
  - Simple Linear Regression
  - Multiple Linear Regression
- The algorithms were implemented using 2 different techniques:
  - Normal Equation
  - Singular Value Decomposiiton (SVD)
 
## Files:
- `simple_linear_regression.ipynb`: contains implementation of simple linear regression using normal equation method
- `multiple_linear_regression.ipynb`: contains implementation of multiple linear regression using normal equation method
- `inear_regression_svd.ipynb`: contains implementation of both simple and multiple linear regression using SVD method

## Remarks:
- Normal Equation method is preferrable when working with small-dimensional datasets
- Normal Equation may fail when dealing with non-invertible matrices
- SVD method will always work regardless
- However, these closed-form solutions of Linear Regression don't scale well as dimensionality of the data increases
  - These methods are very slow and computationally expensive
- It may be preferrable to use iterative solutions like Gradient Descent when dealing with high-dimensional datasets
