Titanic Survival Prediction Model

Overview
This project is a machine learning model that predicts whether a passenger on the Titanic survived based on various factors such as age, gender, ticket class, and more. The model was built as part of an internship task at Encryptix and serves as a classic beginner project in data science and machine learning.

Dataset
The dataset used in this project contains information about the passengers aboard the Titanic. Key features include:

Pclass: Ticket class (1st, 2nd, 3rd)
Sex: Gender of the passenger
Age: Age of the passenger
Fare: Ticket fare
Embarked: Port of Embarkation (C, Q, S)
Survived: Survival status (0 = No, 1 = Yes)
The data is preprocessed to handle missing values, categorical variables, and scaling before training the model.

Project Structure

1. Data Preprocessing:

Handle missing values.
Encode categorical variables.
Scale numerical features.

2. Exploratory Data Analysis (EDA):

Visualizations to understand the distribution of survival rates.
Analysis of key factors affecting survival such as gender, class, and age.

3. Model Training:

A Random Forest Classifier is used to train the model.
The model is evaluated using accuracy scores, confusion matrices, and classification reports.
Feature Importance:

The importance of different features in predicting survival is analyzed and visualized.

Results:-
The model achieved an accuracy of over 80%, demonstrating good performance in predicting survival outcomes on the Titanic dataset.

Key Findings:-
Gender: Women had a higher survival rate, likely due to prioritization during the evacuation.
Ticket Class: First-class passengers had better survival rates, showing the impact of socio-economic status.
Age: Younger passengers were more likely to survive, reflecting the prioritization of children.
