# Explainable AI – Clinical Decision Support System for Diabetes Readmission

## Overview

This project implements an Explainable AI–based Clinical Decision Support System to predict hospital readmission for diabetic patients. The system performs data preprocessing, handles missing values, encodes categorical variables, scales numerical features, and balances the dataset using SMOTE. Multiple machine learning models are trained and compared, and SHAP explainability is used to interpret predictions and highlight important clinical features.

## Features

* Data preprocessing and cleaning
* Handling missing values and categorical encoding
* Feature scaling using StandardScaler
* Class imbalance handling using SMOTE
* Multiple model training and comparison
* Explainable AI using SHAP
* Performance metrics and visualization
* Interactive prediction interface

## Models Used

* Logistic Regression
* Random Forest
* Gradient Boosting
* XGBoost

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score
* Confusion Matrix

## Explainable AI

SHAP (SHapley Additive exPlanations) is used to:

* Identify important features
* Explain model predictions
* Visualize feature impact
* Improve model transparency

## Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* XGBoost
* SHAP
* Matplotlib, Seaborn
* SMOTE (Imbalanced-learn)
* Jupyter Notebook

## Dataset

The system uses a diabetes hospital readmission dataset (`diabetic_data.csv`) containing patient demographics, diagnosis codes, hospital visits, medications, and admission details.

## Workflow

1. Load diabetes dataset
2. Clean and preprocess data
3. Encode categorical variables
4. Scale numerical features
5. Apply SMOTE for class balancing
6. Train multiple ML models
7. Compare model performance
8. Apply SHAP for explainability
9. Display prediction results

## Output

* Model comparison table
* Classification reports
* ROC-AUC scores
* Confusion matrices
* SHAP feature importance plots
* Interactive prediction interface

## Author

Spandana V R
