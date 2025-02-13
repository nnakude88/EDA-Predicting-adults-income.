# EDA-Predicting-adults-income.

Overview

This project focuses on analyzing adult demographic data and predicting whether an individual earns more or less than $50,000 annually based on a variety of attributes. The dataset consists of adult individuals and includes various features such as age, work class, education, marital status, occupation, and others. The goal of the project is to gain insights into the relationships between these features and income, as well as to build predictive models to classify income levels.

# Dataset Description

The dataset used in this project is stored in a CSV format and contains the following columns:

# Column Name	Description
age	Age of the individual.

workclass	The type of employment or working class of the individual (e.g., Private, Self-Employed, etc.).

fnlwgt	Final weight of the individual, which is a weighting factor used to balance the dataset.

education	The highest level of education attained by the individual (e.g., Bachelors, Masters, etc.).

education.num	Numeric representation of the level of education (e.g., 13 for Bachelors, 14 for Masters).

marital.status	Marital status of the individual (e.g., Married, Single, Divorced, etc.).

occupation	Occupation or profession of the individual (e.g., Tech Support, Exec-managerial, etc.).

relationship	Relationship status of the individual (e.g., Husband, Wife, Not-in-family, etc.).

race	Racial background of the individual (e.g., White, Black, Asian, etc.).

sex	Gender of the individual (Male or Female).

capital.gain	Amount of capital gained by the individual in the past year (e.g., from investments).

capital.loss	Amount of capital lost by the individual in the past year (e.g., from investments).

hours.per.week	Number of hours the individual works per week.

native.country	Country of origin of the individual (e.g., United States, Mexico, etc.).

income	The income class of the individual, which indicates if the individual earns more than $50K. (Target Variable)

# Target Variable:

income: This column indicates whether the individual earns more than $50,000 per year. The goal is to predict this class based on the other features in the dataset.

# Objectives

The main objectives of this analysis are:

Exploratory Data Analysis (EDA): Explore the dataset to uncover trends, correlations, and insights related to adult income.

Data Preprocessing: Handle missing values, outliers, and categorical variables.

 Feature Engineering: Create new features or modify existing ones to improve the model performance.

Model Building: Train and evaluate various machine learning models to predict income class based on the given features.

Model Evaluation: Assess the performance of the models using suitable metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

# Data Preprocessing Steps

Missing Data: Handle missing values in the dataset by using strategies such as filling with the mean, mode, or using imputation methods.

Categorical Encoding: Encode categorical variables such as workclass, education, marital.status, etc., using techniques like one-hot encoding or label encoding.

Feature Scaling: Standardize or normalize continuous features like age, fnlwgt, capital.gain, capital.loss, hours.per.week to ensure they are on a similar scale.

Outlier Detection: Detect and handle outliers in continuous features using methods like Z-score or IQR-based methods.

# Model Building
This project uses several machine learning algorithms to predict income class (<=50K or >50K):

Logistic Regression: A baseline model for binary classification.

Decision Trees: A non-linear model that can capture interactions between features.

Random Forest: An ensemble method that combines multiple decision trees to improve performance.

Support Vector Machines (SVM): A powerful classification algorithm based on the margin maximization principle.

Gradient Boosting Machines (GBM): A robust ensemble method that iteratively improves the model's performance.

The dataset will be split into training and testing sets, with a typical ratio of 80:20 

# Evaluation Metrics

The performance of the models will be evaluated using the following metrics:

precision    recall  f1-score   support


Conclusion
This project provides valuable insights into the factors that influence adult income, and it demonstrates the use of machine learning techniques to predict whether an individual earns more than $50,000 per year. By analyzing the relationships between various features and income.
