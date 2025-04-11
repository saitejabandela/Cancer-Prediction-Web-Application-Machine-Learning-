# Cancer-Prediction-Web-Application-(Machine Learning)

# Overview
This repository contains a full-stack web application designed to predict the likelihood of cancer based on user-reported symptoms. It integrates a machine learning model into a user-friendly interface, allowing real-time prediction based on input data.

Backend: Python-based server for machine learning model inference and training.

Frontend: Simple web interface for user interaction and result visualization.

Model: Trained Logistic Regression classifier using health symptom data.

# Key Features
Symptom Input Form: Interactive frontend for users to enter symptoms.

ML-Based Prediction: Real-time inference using a trained logistic regression model.

Model Training Pipeline: Backend includes scripts for preprocessing, training, and evaluation.

Model Persistence: The trained model is saved as model.pkl and reloaded for predictions.

# Machine Learning Details
Libraries Used:

numpy, pandas, matplotlib, scikit-learn, pickle

Algorithm:

Logistic Regression

Dataset:

Cancer.csv – Contains features related to common cancer symptoms and patient information.

# Data Preprocessing Steps
Drop irrelevant or non-numeric columns: Patient Id, Gender, Age

Encode categorical variables

Normalize feature values for model efficiency

# Model Training
The model is trained using Logistic Regression.

Evaluation is done using accuracy score.

The trained model is saved as a .pkl file using the pickle module.
