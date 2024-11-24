# Breast-Cancer-Classification-Machine-Learning
# Project Overview
This project aims to classify breast tumors as malignant or benign using the Breast Cancer Wisconsin dataset from the scikit-learn library. The goal is to build and evaluate machine learning models for accurate predictions, aiding early detection and better healthcare outcomes.

# Dataset Description
Source: Breast Cancer Wisconsin (Diagnostic) dataset from scikit-learn.
Features: 30 numerical features describing cell nucleus characteristics (e.g., radius, texture, perimeter).
Target:
0: Malignant
1: Benign

### Steps Completed
# 1.Data Collection
Loaded the dataset directly from scikit-learn.
# 2.Exploratory Data Analysis (EDA)
Analyzed feature distributions and correlations using visualizations like heatmaps, pair plots, and histograms.
# 3.Data Cleaning
Verified the dataset for missing and duplicate values.
# 4.Outlier Detection and Handling
Identified and handled outliers using the IQR method to improve data quality.
# 5.Data Transformation
Applied PowerTransformer to handle skewed data.
# 6.Feature Engineering
Selected meaningful features using Variance Threshold and Random Forest feature importance methods.
# 7.Data Splitting
Split the dataset into training (80%) and testing (20%) subsets.
# 8.Feature Scaling
Standardized and normalized features using StandardScaler and MinMaxScaler.
# 9.Model Implementation
Built five classification models:
Logistic Regression
Decision Tree
Random Forest
Support Vector Machine (SVM)
k-Nearest Neighbors (k-NN)
# 10.Model Evaluation
Evaluated models using accuracy, confusion matrices, and classification metrics like precision, recall, and F1-score.
# 11.Model Comparison
Compared the performance of all models to identify the best and worst-performing algorithms.
# 12.Interpretation of Results
Analyzed model outcomes and drew insights regarding feature importance and prediction accuracy.
# Usage
Run the code sequentially to load, preprocess, and evaluate the dataset.
Compare model performance 
