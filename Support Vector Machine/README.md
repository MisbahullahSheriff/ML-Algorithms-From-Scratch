# Support Vector Machine from Scratch

## Overview:
- There're 2 types of Linear Support Vector Machine Classifier algorithms:
  - Hard Margin SVM
  - Soft Margin SVM
- This folder contains the code for implementing the Soft Margin Support Vector Machine Classifier algorithm using Gradient Descent

## Files:
- `svm.ipynb`: contains implementation of soft-margin svm classifier using gradient descent

## Remarks:
- Soft Margin SVM allows for some misclassifications in order to improve generalization performance
- Soft Margin SVM is suitable when we don't have perfectly linearly separable datasets
- Hard Margin SVM only works on perfectly linearly separable datasets
- Both Hard Margin and Soft Margin SVMs learn a linear decision boundary
- SVMs be extended to cater to non-linearly separable datasets via the `kernel trick`
- SVMs are very good in handling high-dimensional datasets as long the size of the dataset isn't very large
