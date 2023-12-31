# Logistic Regression from Scratch

## Overview:
- This folder contains the code for implementing:
  - Logistic Regression
  - Softmax Regression
- Logistic Regression is used for solving binary classification problems
- Softmax Regression is an extension of Logistic Regression
  - Used for solving multi-class classification problems directly
 
## Files:
- `logistic_regression.ipynb`: contains implementation of logistic regression using gradient descent
- `softmax_regression.ipynb`: contains implementation of softmax regression using gradient descent

## Remarks:
- There's no closed-form solution for the logistic regression algorithm
- Logistic Regression can also be used for solving multi-class classification problems indirectly via:
  - one-vs-rest
  - one-vs-one
- Softmax Regression can be used for solving multi-class classification problems directly
- Both, logistic regression and softmax regression were implemented using gradient descent
- Both algorithms require feature scaling for better performance and results
