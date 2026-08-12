# Customer Churn Prediction using Machine Learning

A Machine Learning project that predicts whether a customer is likely to churn based on customer and service-related information.

## 📌 Project Overview

Customer churn is an important business problem where companies need to identify customers who are likely to leave their services.

In this project, Machine Learning classification algorithms are used to predict customer churn. The project covers the complete workflow from data preprocessing and model training to evaluation and deployment using Streamlit.

## 🎯 Objective

The main objectives of this project are:

- Clean and preprocess customer data
- Perform exploratory data analysis
- Build classification models
- Compare different Machine Learning algorithms
- Evaluate model performance
- Develop a user-friendly prediction application using Streamlit

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook
- Streamlit
- Git & GitHub

## 📂 Dataset

The project uses the Telco Customer Churn dataset.

The dataset contains customer information related to:

- Customer demographics
- Services used
- Account information
- Contract details
- Payment methods
- Churn status

## 🔄 Project Workflow

1. Data collection
2. Data exploration
3. Data cleaning
4. Data preprocessing
5. Feature preparation
6. Train-test split
7. Model training
8. Model evaluation
9. Model comparison
10. Streamlit application development

## 🤖 Machine Learning Models

Two classification algorithms were implemented and compared:

### 1. Logistic Regression

Accuracy: **81.97%**

### 2. Decision Tree

Accuracy: **70.83%**

Based on the results, Logistic Regression performed better than the Decision Tree on the given dataset.

## 📊 Model Evaluation

The models were evaluated using classification metrics including:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## 🖥️ Streamlit Application

A Streamlit web application was developed to provide customer churn predictions through an interactive interface.

The trained model and supporting preprocessing files are used by the application to generate predictions.

## 📁 Project Structure

```text
Customer-Churn-Prediction-ML/
│
├── app.py
├── Classification_Project.ipynb
├── customer_churn_model.pkl
├── feature_names.pkl
├── scaler.pkl
├── requirements.txt
├── README.md
├── LICENSE
├── .gitignore
└── WA_Fn-UseC_-Telco-Customer-Churn.csv