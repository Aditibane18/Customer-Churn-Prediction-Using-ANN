# Telecom Customer Churn Prediction using Artificial Neural Networks (ANN)

## Overview
This project aims to predict customer churn in a telecom industry using Artificial Neural Networks (ANN). Customer churn refers to the phenomenon where customers stop using the services provided by a company. By accurately predicting churn, telecom companies can take proactive measures to retain customers and improve customer satisfaction.

The project utilizes historical customer data such as demographics, usage patterns, and service subscriptions to train an ANN model. The trained model then predicts whether a customer is likely to churn or not based on new data inputs.

## Prerequisites
- Python 3.x
- TensorFlow
- Keras
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook (for running the provided notebooks)

## Dataset
The dataset used for this project contains historical customer data, including features such as:
- Customer demographics (gender, SeniorCitizen, Partner, Dependents)
- Tenure (duration of the customer's subscription)
- Services subscribed (PhoneService, MultipleLines, InternetService, OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies)
- Contract details (Contract, PaperlessBilling, PaymentMethod)
- Financial information (MonthlyCharges, TotalCharges)
- Churn label (whether the customer churned or not)

## Usage
1. Data Preprocessing:
- Explore and preprocess the dataset using provided Jupyter notebooks (`customer_churn.ipynb`).
- Perform data cleaning, feature engineering, and normalization as necessary.

2. Model Training:
- Train the ANN model using the preprocessed data.
- Experiment with different architectures, hyperparameters, and regularization techniques to improve model performance.

3. Model Evaluation:
- Evaluate the trained model using performance metrics such as accuracy, precision, recall, and F1-score.
- Analyze the confusion matrix to assess the model's predictive power.

4. Deployment:
- Deploy the trained model in a production environment for real-time churn prediction.
- Integrate the model with existing CRM systems or customer management platforms.
