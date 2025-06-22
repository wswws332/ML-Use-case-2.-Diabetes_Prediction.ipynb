

Project Overview
This project is a machine learning-based solution that predicts whether a person is likely to be diabetic based on diagnostic measurements. 
The notebook is part of a collection of ML use cases and focuses on binary classification.
Dataset
Source: Pima Indians Diabetes Dataset

Features:

Pregnancies
Glucose
BloodPressure
SkinThickness
Insulin
BMI
DiabetesPedigreeFunction
Age
Outcome (0 = Non-diabetic, 1 = Diabetic)

Objective:
To build a model that can accurately classify patients as diabetic or non-diabetic using various health indicators.

Steps Performed
Data Exploration & Visualization

Summary statistics

Correlation matrix

Missing value treatment (e.g., replacing 0s with mean/median in some columns)

Data Preprocessing

Scaling (StandardScaler / MinMaxScaler)

Encoding (if applicable)

Train-test split

Model Training

Tried multiple models: Logistic Regression, Random Forest, SVM, etc.

Hyperparameter tuning (GridSearchCV or RandomizedSearchCV)

Model Evaluation

Accuracy, Precision, Recall, F1-score

Confusion matrix

ROC-AUC curve


ML Models Used
Logistic Regression

Random Forest Classifier

Support Vector Machine

Decision Tree

k-NN (optional)

XGBoost (optional)

| Model               | Accuracy | Precision | Recall | F1-Score |
| ------------------- | -------- | --------- | ------ | -------- |
| Logistic Regression | 78%      | 0.76      | 0.74   | 0.75     |
| Random Forest       | 81%      | 0.80      | 0.79   | 0.79     |




