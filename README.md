Titanic - Data Processing and Machine Learning

Project Overview

This project focuses on exploring and processing the Titanic dataset and building a first machine learning classification model to predict passenger survival.

The project is part of my practical learning journey in Data Science and Machine Learning.

Dataset

- Source: "Kaggle Titanic Competition" (https://www.kaggle.com/competitions/titanic/data)
- Original dataset: 891 rows and 12 columns.

Work Completed

1. Data Processing

- Handling missing values.
- Checking duplicate records.
- Extracting Deck information from Cabin.
- Checking data types.
- Detecting potential outliers using the IQR method.

2. Feature Engineering

- Creating FamilySize.
- Creating IsAlone.
- Extracting passenger titles from Name.
- Grouping rare titles.

3. Encoding

- One-Hot Encoding for Sex, Embarked, Deck, and Title.
- Preparing Pclass as a numerical feature.

4. Exploratory Data Analysis

- Survival distribution.
- Survival rate by gender.
- Survival rate by passenger class.
- Survival rate by age group.
- Survival rate by family group.
- Survival rate by fare group.

5. Machine Learning

- Separating features and target.
- Train-Test Split (80% training, 20% testing).
- Training a Logistic Regression model.
- Evaluating model performance.

Model Results

Logistic Regression

Metric| Score
Accuracy| 84.36%
Precision| 82.54%
Recall| 75.36%
F1-Score| 78.79%

Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

Current Status

The initial data processing, exploratory analysis, and Logistic Regression baseline have been completed.

Further work is planned, including feature scaling, additional classification models, and model comparison.

What I Learned

This project helped me practice data cleaning, feature engineering, exploratory data analysis, classification, and model evaluation.
