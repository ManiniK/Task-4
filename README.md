# Task-4 - Logistic Regression 

## Overview
Logistic Regression model to classify tumors as Malignant (1) or Benign (0) using the Breast Cancer Wisconsin dataset.  
Includes preprocessing, model training, evaluation, and threshold tuning.

## Steps
1. Data Preparation: Load CSV, drop unused columns, map target to binary.  
2. Preprocessing: Stratified train-test split, feature scaling.  
3. Model: Logistic Regression (liblinear, max_iter=1000).  
4. Evaluation: Accuracy, Confusion Matrix, Precision, Recall, F1-score, ROC-AUC, ROC and PR curves.  
5. Analysis: Optimal thresholds using F1-score and Youden’s J statistic.
