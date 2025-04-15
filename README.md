# Titanic Survival Prediction
This project showcases Machine Learning (ML) models, Data Preprocessing, and Exploratory Data Analysis (EDA) using the Titanic survival dataset. The goal is to predict the survival of passengers on the Titanic based on various features, such as age, sex, class, and more. The project demonstrates multiple ML models and data preprocessing techniques to improve prediction accuracy.
## Project Overview

The Titanic dataset contains details about passengers on the Titanic. The goal of this project is to predict whether a passenger survived or not based on features such as:

- Pclass (Passenger class)
- Sex
- Age 
- SibSp (Number of siblings or spouses aboard)
- Parch (Number of parents or children aboard)
- Fare
- Embarked (Embarkation location)

## Exploratory Data Analysis (EDA)

In this section, several visualizations and statistical analyses are used to uncover relationships and patterns:

- Survival Rate by Class, Sex, and Age: Analyzing how survival rates differ by passenger class, gender, and age.
- Feature Distribution: Visualizing the distribution of features such as Age, Fare, and Pclass.
- Correlations: Identifying correlations between numeric features and how they relate to survival.
- Visualizing Missing Data: Exploring the missing values in the dataset using a heatmap.

## Data Preprocessing

The data preprocessing steps include:

- Handling Missing Values: Using techniques like imputation for Age and Embarked, and filling missing Fare values.
- Feature Engineering: Creating new features like FamilySize. Extracting titles from the Name column.
- Categorical Encoding: Converting categorical variables such as Sex and Embarked into numerical values using techniques like Label Encoding and One-Hot Encoding.
- Scaling: Standardizing continuous variables (like Age and Fare) using StandardScaler and Min-Max Scaling.

##  Machine Learning:
The following machine learning models are implemented and evaluated:

- Random Forest Classifier: An ensemble method using multiple decision trees.
- Decision Tree Classifier: A model that splits data into subsets based on feature values.
- Linear SVC: A linear model for classification.
- K-Nearest Neighbors Classifier: A non-parametric algorithm that classifies based on proximity to other points.
- Gaussian Naive Bayes: A probabilistic classifier based on Bayes' Theorem.
- CatBoost Classifier: A gradient boosting model known for handling categorical features efficiently.
