# Module 20 Report 

## Overview of the Analysis

* The purpose of this analysis was to train and evaluate machine learning models pertaining to loan risk. 
* The financial data provided information on loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks and total debt to predict loan status.
* I was trying to predict loan_status of loans based on the variables listed above. If the code predicted a value of 0, the loan was healthy. If it returned a 1, the loan was at high risk of defaulting.
* In order to accomplish this, I first split the data into two sets - training and test. I then created a logistic regression model with the data and retrieved a classification report to retrieve the data.


## Results

* The confusion matrix and classification report gave scores for two possibilities. 0 indicates the loan is healthy while 1 indicates the loan is at high risk of defaulting.
    * The 0 resulted in a 1.00 precision, a .00 recall, a 1.00 f1-score, and a 18765 support. This indicates the test was 100% accurate in its predictions. 
    * The 1 resulted in a .84 precision, a .94 recall, a .89 f1-score, and 619 support. This indicates the test was not always accurate in its predicitons and there is room for improvement.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* The test seems to work best to identify healthy loans, while it does not do as good of a job predicting loans that are at high risk of going into default. I would still recommend using this test despite it not being perfect, as the accuracy is still very high for both results. 
