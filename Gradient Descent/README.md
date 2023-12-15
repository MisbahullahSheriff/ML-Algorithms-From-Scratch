# Gradient Descent from Scratch

## Overview:
- This folder contains the code for implementing 3 variants of the Gradient Descent algorithm:
  - Batch Gradient Descent
  - Stochastic Gradient Descent
  - Mini-batch Gradient Descent
- The final results of the 3 different algorithms are analyzed with visualizations and a tabular summary

## Files:
- `gradient_descent.ipynb`: contains implementation of the 3 variants of the gradient descent algorithm

## Remarks:
- Batch Gradient Descent goes over the entire training data in each iteration
  - It's computationally expensive as the no. of observations increases
  - It is guaranteed to converge at the global minimum when optimizing a convex function
  - The path towards the minimum is smooth
- Stochastic Gradient Descent goes over a single observation in each iteration:
  - It's computationally very fast
  - The path towards the minimum is squiggly
  - Doesn't fully coonverge at the minimum point but reaches its vicinity eventually with a good learning shcedule
  - Helps avoid any local minima
  - Good to use when optimizng any non-convex functions
- Mini-batch Gradient Descent goes over a bunch of observations in each iteration:
  - Faster than Batch Gradient Descent but slower than Stochastic Gradient Descent
  - The path towards the minimum is less squiggly
