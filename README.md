# Titanic: Machine Learning from Disaster from Kaggle Competition

This repository contains my solution proposal for the Titanic competition hosted on Kaggle. Feel free to connect with me on LinkedIn and explore my other projects on GitHub.

- [LinkedIn](https://www.linkedin.com/in/andré-fernandes-868006207/)
- [GitHub](https://github.com/vBarFace)

## Table of Contents
1. [Introduction](#Introduction)
2. [Data Description](#Data-Description)
3. [Exploratory Data Analysis (EDA)](#Exploratory-Data-Analysis-EDA)
4. [Data Preprocessing](#Data-Preprocessing)
5. [Modeling](#Modeling)
6. [Model Evaluation](#Model-Evaluation)
7. [Conclusion](#Conclusion)
8. [References](#References)

## Introduction
The Titanic dataset is a classic machine learning problem from the Titanic disaster in 1912. This repository contains code and analysis that aim to predict which passengers survived based on attributes such as age, gender, class, and more.

For details about the competition, visit [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic/overview).

## Data Description
The dataset consists of two main files:
- `train.csv`: The training dataset
- `test.csv`: The test dataset

### Data Dictionary
- **PassengerId**: Unique ID for each passenger
- **Survived**: Survival (0 = No, 1 = Yes)
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Name**: Name of the passenger
- **Sex**: Gender
- **Age**: Age in years
- **SibSp**: Number of siblings/spouses aboard the Titanic
- **Parch**: Number of parents/children aboard the Titanic
- **Ticket**: Ticket number
- **Fare**: Passenger fare
- **Cabin**: Cabin number
- **Embarked**: Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

## Exploratory Data Analysis (EDA)
Exploratory Data Analysis reveals insights and patterns within the dataset. Visualizations are used to understand the distribution of features and their relationships with survival.

## Data Preprocessing
Data preprocessing involves handling missing values, encoding categorical variables, feature engineering, and scaling numerical features to prepare the data for modeling.

## Modeling
Several machine learning models are implemented to predict passenger survival:
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine
- K-Nearest Neighbors

## Model Evaluation
Models are evaluated using metrics such as accuracy, precision, recall, and F1-score. Cross-validation ensures the models' robustness and generalizability.

## Conclusion
The project concludes with a summary of findings from EDA, preprocessing steps, and model performances. Potential improvements and next steps are also discussed.

## References
- [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic/overview)
- [Kaggle Titanic Tutorial](https://www.kaggle.com/code/alexisbcook/titanic-tutorial)
