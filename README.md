# Student Result Predictor – Logistic Regression

## Overview
This project is a Machine Learning mini-project that predicts **student grade categories (A/B/C/D)** based on academic and lifestyle factors such as study hours, attendance, participation, sleep, stress, and previous academic performance.  
The model is built using **Logistic Regression** and standard data preprocessing techniques.

---

## Problem Statement
To classify a student’s final grade category using multiple behavioral and academic features instead of predicting exact marks.

---

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-Learn

---

## Features Used
- Study Hours
- Attendance Percentage
- Class Participation
- Sleep Hours
- Previous Grade
- Internet Access
- Extra Activities
- Parent Education
- Stress Level

---

## Workflow
1. Data Loading using Pandas  
2. Data Cleaning & Column Removal (Student ID)  
3. One-Hot Encoding for Categorical Features  
4. Label Encoding for Target Variable  
5. Train–Test Split with Stratification  
6. Feature Scaling using MinMaxScaler  
7. Logistic Regression Model Training  
8. Model Evaluation using Accuracy & Confusion Matrix  
9. Live Student Grade Prediction Demo  

---

## Model
**Logistic Regression Classifier**

Chosen because the task is a **classification problem** rather than regression.

---

## Results
- Initial synthetic dataset produced unrealistically high accuracy due to linear separability.
- Controlled noise and class overlap were introduced to simulate real-world uncertainty.
- Final Accuracy: **~83%**

---

## Key Learning Outcomes
- Handling categorical data with One-Hot Encoding  
- Avoiding data leakage  
- Understanding overfitting and linear separability  
- Evaluating models using confusion matrix  
- Building a complete ML pipeline end-to-end  



