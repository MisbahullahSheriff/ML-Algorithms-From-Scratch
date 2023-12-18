# Naive Bayes from Scratch

## Overview:
- This folder contains the code for implementing 3 variants of the Naive Bayes Classification algorithm:
  - Bernoulli Naive Bayes
  - Multinomial Naive Bayes
  - Gaussian Naive Bayes
- Naive Bayes is a linear classification model
- The implementations of the Naive Bayes algorithm vary based on the nature of the input features
 
## Files:
- `bernoulli_nb.ipynb`: contains implementation of bernoulli naive bayes classification algorithm
- `multinomial_nb.ipynb`: contains implementation of multinomial naive bayes classification algorithm
- `gaussian_nb.ipynb`: contains implementation of gaussian naive bayes classification algorithm

## Remarks:
- Naive Bayes is a linear classification algorithm, i.e., it learns a linear decision boundary
- It can be used for solving binary and multi-class classification problems directly
- It makes an assumption that the given a class label, the input features are independant of each other
  - This is a very strong assumption, hence the name `naive`
  - This simplifies the math behind the algorithm
  - This assumption is the main foundation of the algorithm
- Bernoulli Naive Bayes:
  - Used when the features are binary
- Multinomial Naive Bayes
  - Used on text data and document classification
- Gaussian Naive Bayes
  - Used when the features are continous and real-valued
- The training procedure is based on the concept of `Maximum Likelihood Estimation`
- Despite the strong assumption, Naive Bayes works well on real-world datasets and is widely used
