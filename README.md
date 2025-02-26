# Pattern Recognition and Machine Learning Assignment (2024-2025)

Assignment for the "Pattern Recognition and Machine Learning" Course\
Faculty of Engineering, AUTh\
School of Electrical and Computer Engineering\
Electronics and Computers Department, 7th Semester\
2024 - 2025

## Overview
This repository contains our implementation for the **Pattern Recognition & Machine Learning** assignment for 2024. The project is divided into four parts (A, B, C, and D), covering different classification methods, probability estimations, and machine learning models.

## Repository Structure
```
├── Team8-AC.ipynb   # Jupyter Notebook for Parts A, B, and C
├── Team8-D.ipynb    # Jupyter Notebook for Part D
├── PR_Assignment_2024.pdf  # Assignment description and requirements
├── labels8.npy      # Predicted labels from Part D
└── README.md        # This documentation
```

## Assignment Breakdown
### Part A: Maximum Likelihood Classifier
- **Objective:** Estimate parameters \(\theta_1\) and \(\theta_2\) for two classes using the Maximum Likelihood Estimation (MLE) method.
- **Implementation:**
  - Compute log-likelihood functions.
  - Visualize the likelihoods.
  - Implement a classifier using the function \( g(x) \).
  - Analyze classification performance.

### Part B: Bayesian Estimation Classifier
- **Objective:** Use Bayesian estimation to refine parameter estimation.
- **Implementation:**
  - Compute posterior distributions.
  - Visualize posterior densities.
  - Implement a Bayesian classifier using \( h(x) \).
  - Compare results with MLE.

### Part C: Decision Tree and Random Forest Classifiers
- **Objective:** Implement classifiers for the **Iris dataset**.
- **Implementation:**
  - Use `DecisionTreeClassifier` from `sklearn`.
  - Experiment with different tree depths and analyze performance.
  - Implement a `RandomForestClassifier` using bootstrap samples.
  - Compare decision boundaries of both classifiers.

### Part D: Custom Classification Model for Large Dataset
- **Objective:** Develop a custom classifier for `datasetTV.csv` and apply it to `datasetTest.csv`.
- **Implementation:**
  - Perform preprocessing and feature selection.
  - Train a model (e.g., SVM, Neural Networks, Random Forest, etc.).
  - Optimize hyperparameters for best accuracy.
  - Predict labels and save them as `labels8.npy`.
  




