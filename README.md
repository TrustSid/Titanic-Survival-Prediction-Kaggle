## Overview
This Jupyter Notebook, Survival_Pred_Titanic.ipynb, contains an analysis and a machine learning model aimed at predicting the survival of passengers on the Titanic. The notebook utilizes the Titanic dataset from Kaggle, which includes various features about the passengers such as age, sex, class, and more. The goal is to build a predictive model that can determine whether a passenger survived or not based on these features.

## Contents
- Data Loading and Exploration: Loading the dataset and performing initial exploration to understand the data.
- Data Preprocessing: Handling missing values, encoding categorical variables, and feature engineering.
- Exploratory Data Analysis (EDA): Visualizations and statistical summaries to uncover insights and relationships in the data.
- Model Building: Training various machine learning models and selecting the best one based on performance metrics.
- Model Evaluation: Evaluating the chosen model using appropriate metrics.
- Conclusion: Summarizing findings and potential next steps.

## Requirements
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Data Description
- PassengerId: Unique ID for each passenger
- Survived: Survival status (0 = No, 1 = Yes)
- Pclass: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)
- Name: Name of the passenger
- Sex: Gender of the passenger
- Age: Age of the passenger
- SibSp: Number of siblings/spouses aboard the Titanic
- Parch: Number of parents/children aboard the Titanic
- Ticket: Ticket number
- Fare: Fare paid by the passenger
- Cabin: Cabin number
- Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

  ## Usage
- Clone the repository (if applicable) or download the notebook file.
- Open the notebook in Jupyter Notebook or Jupyter Lab.
- Run the cells sequentially to reproduce the analysis and model training process.

## Final Model and Results
For the final prediction, we used a **Random Forest classifier**, which achieved an accuracy of 97%. This high accuracy demonstrates the model's effectiveness in predicting the survival of Titanic passengers based on the given features.
