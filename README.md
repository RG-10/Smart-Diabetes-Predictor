# 🔬Smart Diabetes Predictor🔬

📝 **Abstract**

This document contains a report based on the Diabetes Prediction dataset trained using well-known machine learning techniques and models. The author carefully predicts the probability of an individual having diabetes purely based on that individual's body features. Various machine learning models were trained and compared, leading to the selection of the best parameters for optimized prediction accuracy. The best model was deployed on the web using the Flask framework.

## Project Specification 📊

The main objective of this term project is to predict the probability of an individual having diabetes based on diagnostic measures. The dataset includes several medical predictor (independent) variables and one target (dependent) variable, Outcome. The independent variables include the number of pregnancies, glucose levels, blood pressure, skin thickness, insulin levels, BMI, diabetes pedigree function, and age. The primary task is to build a machine learning model that accurately predicts whether or not a patient in the dataset has diabetes.

## Chapter 1: Introduction 🚀

The project report demonstrates the steps and procedures for solving a real-world problem using data science and machine learning. The author uses machine learning to predict whether a person has diabetes based on information such as blood pressure, BMI, and age. The report covers the following sections:

- **Overview**
- **Data Description**
- **Data Exploration**

### 1.1 Overview 🌐

The data was collected and made available by the "National Institute of Diabetes and Digestive and Kidney Diseases." Several constraints were placed on the selection of these instances from a larger database. The diabetes dataset was easily available on Kaggle, providing valuable insights.

### 1.2 Data Description 📊

The dataset includes the following columns:

- Pregnancies: Number of times pregnant
- Glucose: Plasma glucose concentration 2 hours in an oral glucose tolerance test
- Blood Pressure: Diastolic blood pressure (mm Hg)
- Skin Thickness: Triceps skin fold thickness (mm)
- Insulin: 2-Hour serum insulin (mu U/ml)
- BMI: Body mass index (weight in kg/(height in m)^2)
- DiabetesPedigreeFunction: Data on diabetes mellitus history in relatives and genetic relationships
- Age: Age (years)
- Outcome: Class variable (0 or 1)

## Accuracy Scores 📈

| Classifier              | Accuracy   |
|-------------------------|------------|
| Logistic Regression     | 81%        |
| KNN                     | 77%        |
| Random Forest           | 79%        |
| Support Vector Machine  | 81%        |

### Hyperparameter Tuning 🎯

The best parameters for Logistic Regression:
- 'C': 4.893900918477489
- 'solver': 'liblinear'

## Cross Validation Classification Scores 🔄

| Cross Validation   | Precision  | Recall  | F1-score  |
|--------------------|------------|---------|-----------|
| CV                 | 0.749743   | 0.714204| 0.580912  |

## Conclusion 📌

This project was an exciting learning experience. The author gained valuable insights into machine learning and data science techniques. After implementing concepts taught by Dr. Naveed Anwar Butt, the author is now capable of:

- Pre-processing data files
- Performing exploratory data analysis
- Training and testing models using various machine learning algorithms
- Generating best parameters using hyperparameter tuning techniques
- Producing valuable outcomes from raw data for better decision-making
- Deploying trained models on the web with a beautiful UI using the Flask framework.
