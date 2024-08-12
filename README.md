TAsk-1:Titanic Survival Prediction Model

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

Task-2:Movie Rating Prediction Using Python

Overview
This project involves building a predictive model to estimate movie ratings based on various features such as genre, director, and actors. The project utilizes Python for data processing, model training, and evaluation. The goal is to understand the factors influencing movie ratings and to develop a model that accurately predicts these ratings.

Project Steps:-

1. Data Loading and Exploration
Loaded the IMDb movie dataset.
Explored the dataset to understand its structure, data types, and missing values.

2. Data Preprocessing

Handling Missing Values: Filled missing numeric values with the mean of respective columns.
Categorical Encoding: Transformed categorical variables (genre, director, and actors) using Label Encoding.
Feature Scaling: Standardized numerical features (budget, runtime) using StandardScaler.

3. Model Building and Training

Model Selection: Used Linear Regression to predict movie ratings.
Training: Split the dataset into training and testing sets to train the model.
Evaluation: Assessed the model's performance using Root Mean Squared Error (RMSE).

4. Model Evaluation and Visualization

Actual vs. Predicted Ratings: Visualized the relationship between actual and predicted ratings with scatter plots and regression lines.
Residuals Distribution: Plotted the distribution of residuals to analyze prediction errors.

Key Insights:-
Model Performance: The Linear Regression model provided valuable insights into the factors affecting movie ratings and yielded a clear understanding of prediction accuracy.
Visualization Insights: The scatter plot and residuals distribution helped visualize the model's effectiveness and identify areas for improvement.
