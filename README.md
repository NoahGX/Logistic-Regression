# Logistic Regression

## Overview
The purpose of this repository is to primarily focuses the implementation of Logistic Regression for binary classification. Additionally, the `Linear.ipynb` serves as supplementary material, demonstrating the use of linear regression models to predict university GPAs from SAT scores. The logistic regression notebook includes detailed steps for forward and backward computation, gradient computation, and model optimization.

## Features
- **Logistic Regression Notebook**:
  - Detailed implementation of logistic function, cost calculations, and gradient updates.
  - Use of `numpy` for matrix operations and `matplotlib` for visualization of the classification results.
  - Model evaluation through accuracy metrics and loss visualization.
- **Linear Regression Notebook**:
  - Demonstrates both the Normal Equation and Gradient Descent methods for linear regression.
  - Visualization of regression lines and prediction accuracy calculations.

## Usage
- Ensure all prerequisites are installed
- Execute each notebook cell sequentially.

## Prerequisites
- Python 3.x
- Jupyter Notebook or JupyterLab
- Libraries: `numpy`, `matplotlib`, `scikit-learn`

## Input
- **Logistic.ipynb**: input datasets structured with feature sets and binary class labels for training the logistic model.
- **Linear.ipynb**: utilizes the `sat_gpa.csv` file containing data on Math SAT, Verb SAT, and university GPA for the predictions.

## Output
- **Logistic.ipynb**: produces model parameters, visualizes decision boundaries, and outputs classification accuracy and loss metrics.
- **Linear.ipynb**: provides predictions of GPAs based on SAT scores and plots the regression results.

## Notes
- Ensure all necessary datapaths are correctly set up.
- These models require various modifications for deployment and productions use.