# Diabetes Prediction using Machine Learning

## Project Overview
This project predicts whether a person is diabetic or non-diabetic using machine learning algorithms. It uses medical attributes such as glucose, blood pressure, BMI, insulin, age, and other health-related features.

## Problem Statement
Diabetes is one of the most common chronic diseases. Early prediction can help in better diagnosis and treatment. The main objective of this project is to build and compare machine learning models to predict diabetes accurately.

## Dataset Features
The dataset contains the following input features:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age

### Target Variable
- `0` = Non-Diabetic
- `1` = Diabetic

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Imported the dataset
2. Performed data cleaning
3. Checked missing and zero values
4. Performed exploratory data analysis
5. Split the dataset into training and testing sets
6. Applied feature scaling
7. Trained multiple machine learning models
8. Compared model predictions
9. Evaluated model performance

## Models Used
- Linear Regression
- Gaussian Naive Bayes
- Decision Tree Classifier

## Model Evaluation

| Model | Accuracy |
|-------|----------|
| Linear Regression | 78% |
| Gaussian Naive Bayes | 76% |
| Decision Tree Classifier | 74% |
