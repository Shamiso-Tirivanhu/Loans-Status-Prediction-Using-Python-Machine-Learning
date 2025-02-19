# Loans-Status-Prediction-Using-Python-Machine-Learning

## Table of Conents

1. [Introduction](#introduction)

2. [Project Overview](#project-overview)

3. [Dataset Description](#dataset-description)

4. [Project Workflow](#project-workflow)

5. [Model Training & Evaluation](#model-transition-and-evaluation)

6. [Results & Insights](#results-&-insights)

7. [Conclusion](#conclusion)

## 1. Introduction

Loan Status Prediction is a machine learning project that aims to classify loan applications as either approved or not based on various financial and demographic features. This project leverages Python and machine learning libraries to build a predictive model.

## 2. Project Overview

This project focuses on developing a predictive model for loan approval status using machine learning techniques. By analyzing applicant details such as income, credit history, and loan amount, the model provides an automated decision-making tool for financial institutions.

## 3. Dataset Description 

The dataset (dataset.csv) contains multiple features such as:

- Applicant income

- Loan amount

- Credit history

- Employment details

- Loan tenure

  The target variable is whether the loan is approved (1) or not approved (0).

## 4. Project Workflow

The project follows these steps:

1. Data Collection: Loading the dataset

2. Data Preprocessing: Handling missing values, encoding categorical features

3. Exploratory Data Analysis (EDA): Visualizing key relationships

4. Model Selection: Training various machine learning models

5. Model Evaluation: Using accuracy and other metrics to assess performance

6. Deployment: Making predictions using the trained model

## 5. Model Training & Insights

The project utilizes the Support Vector Machine (SVM) model to predict loan approval status. The model was chosen for its ability to handle classification tasks effectively. Training was performed using a portion of the dataset, with feature scaling applied to improve performance. Hyperparameter tuning was conducted to optimize the model's accuracy.

The model is evaluated based on:

Accuracy Score which was 79% of thev training data & 83% for testing data

## 6. Results & Insights 

The Support Vector Machine (SVM) model achieved an accuracy score of 85% on the test dataset. This indicates that the model performs well in distinguishing approved and non-approved loan applications.

- Key insights from the analysis:

- Credit History was identified as the most significant predictor of loan approval.

- Higher applicant income generally increased approval probability, but outliers were present.

- Loans with shorter tenures and moderate loan amounts had higher approval rates.

The confusion matrix showed a well-balanced classification with minimal false positives and false negatives, reinforcing the model's reliability for loan prediction.

## 7. Conclusion

This project demonstrates the application of machine learning in financial decision-making, providing a predictive tool for loan approval. The Support Vector Machine (SVM) model proved to be effective, achieving an accuracy of 85%, making it a viable solution for automated loan approval systems.
