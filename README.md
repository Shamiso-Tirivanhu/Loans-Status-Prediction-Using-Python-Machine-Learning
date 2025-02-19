++# Loans-Status-Prediction-Using-Python-Machine-Learning

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

The diagram below demonstrates the relationship between Loan Status and Married and unmaaried. It depicts that people who are married stand a higher chance of getting a loan as opposed to people who are not married. A plausible reason this might be the case could be that married couples can assist each other in paying back the loan. Whereas, singles might grapple to pay back the loan by themselves.

![image_alt](https://github.com/Shamiso-Tirivanhu/Loans-Status-Prediction-Using-Python-Machine-Learning/blob/3988c0a19cd53d787625512c9fc542344006b506/Loan%20Status%20and%20Married%20.png)










The diagram below illustates the relationship between Loan status and Education. As shown below, Graduates have a higher chance of obtaining a loan as opposed to Non-Graduates. Perhaps the assumption is that a Graduate can pay back the loan since they will be employed, while someone who is not a graduate might fail to pay back the loan.

![image_alt](https://github.com/Shamiso-Tirivanhu/Loans-Status-Prediction-Using-Python-Machine-Learning/blob/e1d4c7efe419d420758e04e052655a4bcd06a22c/Loan_Status%20and%20Education.png)

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

The diagram below shows the Accuracy Score of training and testing data performance.

- Training data is 79%
- Testing data is 83%

It can be argued that the model performed relatively well as there is not much ddifference between the accuracy score of the training and testing data.


![image_alt](https://github.com/Shamiso-Tirivanhu/Loans-Status-Prediction-Using-Python-Machine-Learning/blob/2f493b0bef66ca4860bcf9becd366f85648226cb/Accuracy%20score%20of%20SVM.png)
