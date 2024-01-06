# Heart Disease Prediction

## Overview

The provided Python code focuses on predicting heart disease using various machine learning classifiers, including Logistic Regression, K-Nearest Neighbors (KNN), Naive Bayes, Support Vector Machines (SVM) with both linear and radial basis function (RBF) kernels, Decision Tree, and Random Forest.

## Data Loading and Exploration

- Loading the 'heart.csv' dataset.
- Exploring the dataset using descriptive statistics, null checks, pair plots, and correlation heatmap.

## Data Preprocessing

- Dropping duplicates from the dataset.
- Converting categorical columns 'cp' and 'thal' to object type.
- One-hot encoding categorical columns.
- Splitting the dataset into features (X) and target variable (y).

## Model Training

### Logistic Regression

- Scaling the features using StandardScaler.
- Training a Logistic Regression model.
- Evaluating the performance using confusion matrix, accuracy, f1-score, recall, precision, and ROC-AUC.
- Visualizing the ROC curve.

### K-Nearest Neighbors (KNN)

- Training a KNN model with 7 neighbors.
- Evaluating the performance using confusion matrix, accuracy, and f1-score.
- Visualizing the ROC curve.

### Naive Bayes

- Training a Gaussian Naive Bayes model.
- Evaluating the performance using confusion matrix.

### Support Vector Machines (SVM)

#### Linear Kernel

- Training an SVM model with a linear kernel.
- Evaluating the performance using confusion matrix, f1-score, recall, and ROC-AUC.
- Visualizing the ROC curve.

#### RBF Kernel

- Training an SVM model with an RBF kernel.
- Evaluating the performance using confusion matrix, f1-score, and recall.
- Visualizing the ROC curve.

### Decision Tree

- Training a Decision Tree model.
- Evaluating the performance using confusion matrix, accuracy, f1-score, recall, and ROC-AUC.
- Visualizing the ROC curve.

### Random Forest

- Training a Random Forest model with 10 estimators.
- Evaluating the performance using confusion matrix, accuracy, f1-score, recall, and ROC-AUC.
- Visualizing the ROC curve.

## Model Comparison

- Comparing the average performance of each model using cross-validation.
- Analyzing which algorithm performs the best on average.

## Conclusion

The code provides a comprehensive analysis of different machine learning classifiers for heart disease prediction. It covers model training, evaluation, and comparison to identify the most effective algorithm on average.

## Note

This analysis assumes that the dataset 'heart.csv' contains relevant information for predicting heart disease. Adjustments may be required based on the characteristics of the actual dataset.
