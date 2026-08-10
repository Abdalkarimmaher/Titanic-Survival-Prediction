Titanic Survival Prediction
Project Overview

This project analyzes the famous Titanic dataset from Kaggle.

The project covers the complete data science workflow, including:

Data Cleaning
Exploratory Data Analysis (EDA)
Feature Engineering
Machine Learning
Model Evaluation
Model Comparison
Dataset

Source:

Titanic Dataset (Kaggle)

The dataset contains passenger information such as:

Age
Sex
Passenger Class
Fare
Embarkation Port
Family Information

The target variable is:

Survived
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
Data Cleaning

The following preprocessing steps were performed:

Removed duplicate rows
Handled missing values
Removed the Cabin column
Filled missing Age values using the median
Filled missing Embarked values using the mode
Validated data types
Checked outliers
Exploratory Data Analysis

EDA included:

Survival distribution
Survival by gender
Survival by passenger class
Age distribution
Fare analysis
Family size analysis
Correlation heatmap
Feature Engineering

A new feature was created:

FamilySize = SibSp + Parch + 1
Machine Learning Models

Three models were trained.

Model Accuracy
Logistic Regression 80.45%
Decision Tree 77.65%
Random Forest 81.56%

Random Forest achieved the highest overall performance.

Results

The Random Forest classifier achieved:

Accuracy: 81.56%
Precision: 78.13%
Recall: 72.46%
F1 Score: 75.19%
Project Workflow
Load Data
↓
Data Cleaning
↓
EDA
↓
Feature Engineering
↓
Machine Learning
↓
Model Evaluation
↓
Model Comparison
Future Improvements

Possible future improvements include:

Hyperparameter tuning
Cross-validation
XGBoost
LightGBM
Additional feature engineering
Author

Abdalkarim Abu Mashyaekh

Computer Science Student
