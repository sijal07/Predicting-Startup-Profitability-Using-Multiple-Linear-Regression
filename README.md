# Predicting-Startup-Profitability-Using-Multiple-Linear-Regression




Multiple Linear Regression on 50 Startups Dataset
Project Overview
This project implements a Multiple Linear Regression model to predict the profit of startups based on their spending patterns across different departments and their geographical location.

Dataset Description
The dataset 50_Startups.csv contains information about 50 startups with the following features:

Features (Independent Variables):
R&D Spend: Investment in research and development

Administration: Administrative costs

Marketing Spend: Expenditure on marketing activities

State: Geographical location (California, Florida, or New York)

Target (Dependent Variable):
Profit: The profit earned by the startup

Data Preprocessing Steps
1. Data Encoding
The categorical variable "State" was encoded using One-Hot Encoding

This transformed the single "State" column into three binary columns representing:

California

Florida

New York

This prevents the model from assuming any ordinal relationship between states

2. Data Splitting
The dataset was split into training and test sets

80% of data used for training the model

20% of data reserved for testing model performance

Random state was set to 0 for reproducible results

Model Implementation
Algorithm Used
Linear Regression from scikit-learn library

Multiple linear regression handles multiple independent variables to predict a continuous outcome

Model Training
The model was trained on the preprocessed training data

Learned the relationship between startup expenditures (R&D, Administration, Marketing) and location with profit

Model Evaluation
The trained model was used to make predictions on the test set

Predicted profits were compared against actual profits to evaluate model accuracy

Results show the model's ability to generalize to unseen data
