# Titanic-Logistic-Regression
For this project, we have worked with the Titanic Data Set from Kaggle.

The goal is to predict whether each person survived or deceased in the shipwreck. (binary classification task)

The model's objective is to analyze various features or information about the individuals and make predictions about their survival outcomes based on that data.

Steps of the project:
1. Import all important libraries
2. Reading the titanic_train.csv file into pandas dataframe
3. View the top few rows of the dataframe
4. Exploratory Data Analysis to visualize the data
5. Check for Missing data
6. Data Cleaning: Impute missing values in Age based Pclass (take average of age in Pclass)
7. Data Cleaning: Drop the Cabin Column
8. Data Cleaning: Drop the row in Embarked column that is NaN
9. Feature Engineering
10. Convert categorical features (Sex, Embark) to dummy variables using get_dummies
11. Build a logistic regression model (by splitting the data in 70:30 ratio of train/test)
12. Predict and evaluate the model
13. Analyse Confusion Matrix and Classification Report
