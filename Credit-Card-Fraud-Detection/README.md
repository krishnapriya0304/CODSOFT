# Credit Card Fraud Detection

This project is a Machine Learning model that detects fraudulent credit card transactions based on transaction data. The model analyzes various transaction features and classifies transactions as either fraudulent or genuine.

## Project Description

Credit card fraud is a major concern in the financial industry, as fraudulent transactions can lead to significant financial losses. The objective of this project is to analyze transaction data, handle class imbalance, and build a classification model capable of accurately identifying fraudulent transactions.

## Features Used

- Time
- Amount
- V1 to V28 (Anonymized Features)
- Class (Target Variable)

## Technologies and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)

## Machine Learning Models

- Logistic Regression
- Random Forest Classifier

## Project Workflow

### Data Collection
Load the credit card transaction dataset.

### Data Exploration
Analyze transaction records and class distribution.

### Data Cleaning
Check and handle missing values.

### Data Preprocessing
Scale numerical features using StandardScaler.

### Handling Class Imbalance
Apply SMOTE to balance fraudulent and genuine transactions.

### Feature Selection
Separate independent and dependent variables.

### Model Training
Train Logistic Regression and Random Forest models.

### Model Evaluation
Evaluate performance using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

### Model Comparison
Compare multiple classification algorithms.

## Visualizations

- Class Distribution Plot
- Correlation Heatmap
- Confusion Matrix
- Feature Importance Graph

## Outcome

The model successfully detects fraudulent transactions with high accuracy. SMOTE helps improve fraud detection performance by balancing the dataset.

## Future Enhancements

- Hyperparameter Tuning
- ROC Curve Analysis
- XGBoost Implementation
- Streamlit Deployment

## Dataset

Credit Card Fraud Detection Dataset
