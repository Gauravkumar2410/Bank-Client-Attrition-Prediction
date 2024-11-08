# Bank-Client-Attrition-Prediction

## Overview
This project is a machine learning pipeline for predicting client attrition (churn) in a banking environment. The model identifies customers likely to close their accounts, allowing the bank to implement targeted retention strategies. Predicting attrition helps reduce customer turnover and improve long-term customer satisfaction and profitability.

## Features
- **Data Preprocessing**: Cleaning, encoding, and scaling customer data for model readiness.
- **Exploratory Data Analysis (EDA)**: Visualizations and correlation analyses to understand data patterns.
- **Feature Engineering**: Generating additional features that contribute to predicting churn.
- **Model Selection**: Evaluation of multiple machine learning algorithms, including logistic regression, decision trees, random forests, and gradient boosting.
- **Model Evaluation**: Performance metrics including precision, recall, F1 score, and AUC-ROC to assess model accuracy.
- **Interpretability**: SHAP and feature importance analysis to explain key drivers of client attrition.

## Technologies Used
- **Python**: Data manipulation and machine learning.
- **Pandas & NumPy**: Data preprocessing and feature engineering.
- **Scikit-Learn**: Model training and evaluation.
- **XGBoost / LightGBM**: Gradient boosting models for structured data.
- **Matplotlib & Seaborn**: Data visualization for EDA.
- **SHAP / LIME**: Interpretability of machine learning predictions.

## Project Structure
```plaintext
.
├── data
│   ├── raw_data.csv          # Original dataset
│   ├── processed_data.csv     # Processed dataset
├── notebooks
│   ├── 1_data_preprocessing.ipynb   # Data cleaning and preprocessing
│   ├── 2_eda.ipynb                  # Exploratory data analysis
│   ├── 3_model_training.ipynb       # Model training and evaluation
│   └── 4_model_interpretability.ipynb # Model interpretability
├── src
│   ├── preprocess.py          # Scripts for data preprocessing
│   ├── model.py               # Scripts for model training
│   └── interpret.py           # Scripts for model interpretability
├── README.md                  # Project overview and instructions
└── requirements.txt           # Dependencies
