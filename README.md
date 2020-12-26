# DPhi Final Project Assignment

-  Source            : [Loan or No Loan](https://dphi.tech/practice/challenge/54#data)
-  Training dataset  : [Training Dataset](https://raw.githubusercontent.com/dphi-official/Datasets/master/Loan_Data/loan_train.csv)
-  Testing dataset   : [Testing Dataset](https://raw.githubusercontent.com/dphi-official/Datasets/master/Loan_Data/loan_test.csv)

## Project Description

In this project i make a classification model for predicting if a user can be granted a loan or not. 

## Dataset

There are 491 training-data and 123 testing-data in this dataset. And in the training dataset there are 12 independent columns and 1 dependent column. This dataset attributes like Loan ID, if the loan applicant is married or not, the level of education, applicant’s income etc. 

## Model

In this project i try 3 different type of models Random Forest, XGBoostm, and Linear Regression. And after evaluating all the models i choose Linear Regression because it produces the best f1 score among all of the models.

## Notebook

You can access the notebook in [here](Notebook/DPhi_Assignment_3_Loan.ipynb)

## Web Deployment

You can access the web deployment in [here](templates/index.html)
