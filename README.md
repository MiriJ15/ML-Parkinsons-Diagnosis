# Parkinson's Disease Analysis and Prediction

## Overview
This project involves analyzing and predicting Parkinson's disease using a dataset from the UCI Machine Learning Repository. The focus is on comparing various machine learning models to accurately classify individuals based on given features.

## Data Source
The dataset is sourced from the UCI Machine Learning Repository: [Parkinsons Data Set](https://archive.ics.uci.edu/dataset/174/parkinsons).

## Workflow
1. **Data Loading**: Load data into a Pandas DataFrame.
2. **Exploratory Data Analysis (EDA)**: Visualize the target variable and feature distributions, and perform correlation analysis.
3. **Data Preprocessing**: Scale features and split the dataset.
4. **Model Training and Evaluation**: Train the XGBClassifier and evaluate using accuracy, classification report, confusion matrix, and feature importance. Apply cross-validation with SMOTE for class imbalance and calculate ROC-AUC scores.
5. **Model Comparison**: Evaluate Logistic Regression, SVM, Random Forest, Gradient Boosting, and XGBClassifier. Use cross-validation with SMOTE.
6. **Ensemble Modeling**: Create an Ensemble model using VotingClassifier and compare its performance.

## Objectives
- Identify the most effective model for predicting Parkinson's disease.
- Handle class imbalance using SMOTE.
- Highlight feature importance for prediction.

## Usage
The project is in a Jupyter Notebook, divided into cells for a step-by-step analysis and modeling process.

## Requirements
- Python 3.x
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, imbalanced-learn

## Running the Project
- Clone or download the repository.
- Install required libraries.
- Run the Jupyter Notebook, observing the output of each cell.

## Conclusion
This project demonstrates machine learning applications in medical diagnostics, particularly for handling imbalanced datasets in biomedical fields.
