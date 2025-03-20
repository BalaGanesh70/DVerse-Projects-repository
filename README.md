Parkinson's Disease Identification Project

Overview

This project aims to identify Parkinson's disease in patients using machine learning techniques. The model processes patient data and predicts whether an individual has Parkinson's disease based on detected symptoms.

Features

Machine Learning-based detection of Parkinson’s disease.

Feature scaling applied to ensure accurate predictions.

Considers key indicators such as Voice Tremors, Cough-like disturbances, Speech Irregularities.

Outputs a clear diagnosis for each patient.

Technologies Used
Python

Pandas

NumPy

Scikit-Learn (Machine Learning Model)

StandardScaler for Feature Scaling

Installation & Setup

Install the required Python packages:

Load the dataset into the project.

Run the script to get predictions for test patients.

Expected Output : ("**Patient 1** (Actual: Parkinson’s) → **Predicted: Parkinson’s** | Signs Detected: Voice Tremors, Cough-like disturbances, Speech Irregularities")
("**Patient 2** (Actual: Healthy) → **Predicted: Healthy** | Signs Detected: None")

How It Works : 

Data Processing: Ensures test data matches the training data's features.

Feature Scaling: Applies the same scaling as used during model training.

Prediction: Uses a trained model to classify patients as either Parkinson's or Healthy.

Interpretation: Generates a report with detected signs and the predicted label.

Usage Instructions

Place new test samples in the provided format.

Run the script, and it will output the diagnosis and detected signs.

Author : S Bala Ganesh 

Developed as part of a Machine Learning project on Parkinson's Disease Identification.
