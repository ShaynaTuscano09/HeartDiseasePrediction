# Heart Disease Prediction



## Introduction

This project aims to predict heart disease accurately using machine learning, facilitating early intervention and personalized healthcare.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Exploration and Analysis](#data-exploration-and-analysis)
- [Data Preprocessing](#data-preprocessing)
- [Model Development](#model-development)
- [Model Evaluation](#model-evaluation)
- [Conclusion](#conclusion)

## Project Overview

The primary goal is to create a machine learning model capable of accurately predicting heart disease likelihood, supporting early intervention and personalized healthcare. The project involves data exploration, preprocessing, and the development and evaluation of machine learning models.

## Data Exploration and Analysis

- Utilized the "Heart Disease Health Indicators Dataset" from Kaggle.
- Explored 22 columns, 21 features, and 1 target variable ('HeartDiseaseorAttack').
- Identified categorical and numerical features, observed outliers, and addressed class imbalance.

## Data Preprocessing

- No missing data; 23,899 duplicate records removed.
- Categorical variables encoded using label encoding.
- Addressed class imbalance using Synthetic Minority Over-sampling Technique (SMOTE).

## Model Development

- Explored Decision Trees, Logistic Regression, Random Forest, Naive Bayes, and KNN.
- Implemented SMOTE on the training set.
- Selected Random Forest and Decision Tree for further consideration.
- Conducted hyperparameter tuning using grid search CV.

## Model Evaluation

- Evaluated both models on test data using accuracy, precision, recall, and F1 score.
- Decision Tree emerged as more efficient for large datasets.

## Conclusion

- Decision Tree selected for efficiency in training on large datasets.
- Notable improvement in model accuracy post-hyperparameter tuning.







