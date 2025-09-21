# Titanic-Survival-Prediction

Project Overview

This project is based on the famous Kaggle Titanic dataset, one of the most popular beginner-friendly machine learning challenges.
The goal is to build a predictive model that determines whether a passenger survived the Titanic disaster or not, based on features such as age, gender, passenger class, family size and more.

Objective

Perform Exploratory Data Analysis (EDA) to understand passenger demographics.
Clean and preprocess data (handle missing values, encode categorical variables, feature engineering).
Train machine learning models to predict survival chances.
Evaluate model accuracy and compare different algorithms.

Steps Involved

Data Cleaning & Preprocessing
Handle missing values (e.g., Age, Cabin, Embarked).
Encode categorical variables (Sex, Embarked).
Feature scaling and engineering.
Exploratory Data Analysis (EDA)
Visualize survival rates by gender, class, age, etc.
Identify correlations and patterns.

Model Building
Logistic Regression
Decision Trees & Random Forest
K-Nearest Neighbors (KNN)
Support Vector Machine (SVM)
Gradient Boosting (XGBoost, LightGBM, etc.)

Model Evaluation
Accuracy, Precision, Recall, F1-score

Insights from Model Comparison
Boosting algorithms (CatBoost, LightGBM, XGBoost) achieved the highest accuracy and F1-scores, making them the best choices for predicting survival.
Ensemble methods (Random Forest) performed strongly, confirming the power of combining multiple decision trees.
Baseline models (Logistic Regression, Decision Tree, Naive Bayes) showed lower accuracy, but they are fast to train and useful for benchmarking.
Neural Network (Keras) was competitive but did not outperform boosting algorithms, showing that sometimes simpler ensemble methods are more effective.
Overall, CatBoost emerged as the best-performing model, offering a good balance between interpretability and performance.

Final Model Comparison – Titanic Survival Prediction
Model	Accuracy	Precision	Recall	F1-Score
CatBoost	0.85	0.83	0.81	0.82
LightGBM	0.84	0.82	0.80	0.81
XGBoost	0.84	0.81	0.80	0.80
Random Forest	0.83	0.80	0.79	0.79
Neural Network (Keras)	0.82	0.80	0.77	0.78
SVM (Linear Kernel)	0.81	0.79	0.77	0.78
Logistic Regression	0.80	0.78	0.76	0.77
KNN (k=5)	0.79	0.76	0.74	0.75
Decision Tree	0.78	0.75	0.74	0.74
Naive Bayes	0.77	0.73	0.72	0.72
