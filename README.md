# Breast Cancer Risk Prediction

## Project Overview

This project aims to predict breast cancer risk by using machine learning methods to classify benign and malignant tumors. The project aims to develop a model for the early diagnosis of breast cancer based on various biological features. This model can assist healthcare professionals in making accurate diagnoses.

## Project Objective

Breast cancer is one of the most common types of cancer among women worldwide. Early diagnosis increases the chances of treatment. This project demonstrates how to develop a machine learning model to predict the risk of breast cancer using various biological data.

## Data Used

The dataset is taken from Kaggle/Breast Cancer Wisconsin (Diagnostic) Data Set. The dataset contains 569 samples and 33 features. The features contain various biological and physical properties of the tumors. These features help in classifying whether the tumors are benign or malignant.

## Methods Used

### Data Exploration
In this phase, the dataset was analyzed in detail and the following operations were performed:

- Checking data types
- Checking for missing values
- Outlier analysis for numerical data
- Scaling operations
- Distribution of the target variable
- Distribution analysis of numerical and object columns

### Data Cleaning

- Encoding for object columns
- Outlier removal for numerical columns
- Skew correction for numerical columns
- Scaling operations were performed

### Modeling
Classification models were created using different machine learning algorithms:

- RandomForest
- XGBoost Classifier
- Logistic Regression

### Cross-validation and Ensemble Model
- To make model validation more reliable, cross-validation was performed, and then an ensemble method was used to create a stronger model.

## Model Performance

The model's accuracy, precision, recall, and F1-score were evaluated. The Logistic Regression model achieved the highest performance.

### Model Performance Metrics:
- **Accuracy**: 0.99
- **Precision**:
  - **Benign (0)**: 0.98
  - **Malignant (1)**: 1.00
- **Recall**:
  - **Benign (0)**: 1.00
  - **Malignant (1)**: 0.95
- **F1-Score**:
  - **Benign (0)**: 0.99
  - **Malignant (1)**: 0.97

### Overall Results:
- **Accuracy**: 0.99
- **Macro Average**:
  - **Precision**: 0.99
  - **Recall**: 0.97
  - **F1-Score**: 0.98
- **Weighted Average**:
  - **Precision**: 0.99
  - **Recall**: 0.99
  - **F1-Score**: 0.99


## Running the Project
To install the required dependencies, run:
```bash
pip install -r requirements.txt


