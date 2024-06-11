# Customer Churn Prediction - ML CodSoft Project 3
This project aims to predict customer churn for a subscription-based service using various machine learning models, including Random Forest, Gradient Boosting, and Logistic Regression.

## Project Overview
Customer churn prediction is crucial for subscription-based businesses to retain customers and improve services. This project uses historical customer data, including features like usage behavior and customer demographics, to predict churn.

## Requirements
Python 3.x
pandas
numpy
scikit-learn
matplotlib
seaborn

## Dataset
The dataset used in this project is Churn_Modelling.csv. It includes customer information such as:

CustomerId
Geography
Gender
Age
Tenure
Balance
NumOfProducts
HasCrCard
IsActiveMember
EstimatedSalary
Exited (Target variable)

## Project Steps
### 1. Data Loading and Preprocessing
Loading Data: The dataset is loaded using pandas.
Data Cleaning: Unnecessary columns are removed.
Encoding Categorical Variables: Label encoding is used to convert categorical variables like Gender and Geography into numerical format.
### 2. Data Splitting
Train-Test Split: The dataset is split into training and testing sets using train_test_split from scikit-learn, with 70% data for training and 30% for testing.
### 3. Model Training and Evaluation
Random Forest Classifier
Model Training: A Random Forest classifier is trained on the training data.
Evaluation: The model's performance is evaluated using accuracy, classification report, confusion matrix, and ROC curve.
Gradient Boosting Classifier
Model Training: A Gradient Boosting classifier is trained on the training data.
Evaluation: The model's performance is evaluated using the same metrics as the Random Forest classifier.
Logistic Regression
Model Training: A Logistic Regression model is trained on the training data.
Evaluation: The model's performance is evaluated using the same metrics as the other classifiers.
### 4. ROC Curve Plotting
Plotting ROC Curves: ROC curves are plotted for all three models to compare their performance visually.
### 5. Feature Importance for Random Forest
Feature Importance: The importance of each feature is extracted from the Random Forest model and visualized using a bar plot to understand which features contribute most to predicting churn.

## Conclusion
This project demonstrates the use of Random Forest, Gradient Boosting, and Logistic Regression to predict customer churn. The Random Forest model's feature importance provides insights into which features contribute most to predicting churn.
