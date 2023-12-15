# Bagging Ensembles from Scratch

## Overview:
- This folder contains the code for implementing 2 variants of the Bagging algorithm:
  - Bagging Classifier
  - Bagging Regressor
- The base estimators were implemented using `Majority Voting`

## Files:
- `bagging_classifier.ipynb`: contains implementation of bagging classifier
- `bagging_regressor.ipynb`: contains implementation of bagging regressor

## Remarks:
- Bagging is an effective `Ensemble` technique
- We can use any valid estimator in the Bagging algorithm
- It's a very efficient and a powerful technique for improving predictive performance of models
- The predictions of the base estimators can be combined in many ways:
  - Majority Voting
  - Weighted Voting
  - Dempster-Schafer Theory
  - Entropy
- Diversity among the base estimators and model aggregation are the key ingredients to successful ensemble modelling
