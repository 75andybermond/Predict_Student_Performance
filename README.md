# Student Performance Prediction

**This project is focused on predicting the final grades of secondary school students using data from two public schools in Portugal. The dataset consists of two csv files: student-mat.csv and student-por.csv. Both files can be downloaded from the following link: http://archive.ics.uci.edu/ml/datasets/Student+Performance.**

## Context
The data was collected during the 2005-2006 academic year and consists of 33 variables, including demographic information about the students (such as age, gender, and family size), information about their home and school environments (such as travel time, extra educational support, and internet access), and their grades in Mathematics and Portuguese.

## Goal
The goal of this project is to build a predictive model for the final grade (G3) of students in both datasets. In addition to predicting G3, we will also explore the relationships between G3 and other variables in the dataset.

## Steps
The following steps will be performed in this project:

Load the data sets (student-mat.csv and student-por.csv)
Explore the datasets and visualize the distributions of the variables
Preprocess the data, including handling missing values, encoding categorical variables, and scaling numerical variables
Split the data into training and testing sets
Train and evaluate several machine learning models, including linear regression, decision tree, random forest, and gradient boosting
Select the best performing model and tune its hyperparameters
Use the final model to make predictions on the testing set
Interpret the results and draw conclusions

## Libraries Used
This project will utilize several Python libraries, including:

Pandas: for data manipulation and preprocessing
NumPy: for numerical computing
Scikit-Learn: for machine learning modeling and evaluation
Matplotlib and seaborn: for data visualization
sklearn for preprocessing and model selection
statsmodels for statistical analysis