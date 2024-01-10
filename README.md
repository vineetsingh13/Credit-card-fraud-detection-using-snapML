# Credit-card-fraud-detection-using-snapML

## Credit Card Fraud Detection Using Decision Tree and SVM (snapML Library)
This repository contains code for predicting credit card fraud using the Decision Tree and SVM algorithms from the snapML library. The dataset used is from Kaggle and includes features such as time, transaction amounts, and various V1-V28 features. The goal is to predict the 'Class' variable, indicating whether a transaction is fraudulent or not.

## Dataset
The dataset used is a tabular dataset with the following columns:

 - Time
 - V1-V28 (features)
 - Amount
 - Class (fraud or not fraud)
 - 
## Decision Tree and SVM Classification
The Decision Tree and SVM algorithms from the snapML library are implemented to predict credit card fraud based on the features excluding 'Time'.

## Data Preprocessing
 - The data is split into training and testing sets (70% training, 30% testing).
 - The dataset is highly unbalanced, so it is balanced by standardizing and normalizing.
 - The prediction class is highly imbalanced, and its weight is balanced using the compute_sample_weight function.

## Model Training and Comparison
Both the Decision Tree and SVM models are trained using snapML, and the training time is compared between snapML's Decision Tree and scikit-learn's Decision Tree.

## Code Execution Environment
The code has been implemented using Python and executed in Google Colaboratory. Google Colaboratory provides a free and convenient platform for running Python code in a Jupyter notebook environment.


## Dependencies
The following Python libraries are used in the implementation:

 - pandas
 - numpy
 - scikit-learn
 - snapML
