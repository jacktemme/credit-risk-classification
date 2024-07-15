# Module 12 Report 

## Overview of the Analysis

This repository employs a logistic regression model from the Scikit-learn library to predict loan risk based on historical lending data. The model is trained on 80% of the data, using features such as the borrower's debt, income, and derogatory marks to assess loan risk, categorized as either healthy or high risk. The remaining 20% of the data is used to evaluate the model's performance by comparing predicted loan outcomes with actual results. The goal of this model is to help the loan company better assess the potential risks of loans, enabling more informed decision-making.


## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Logistic Regression Machine Learning Model:
    * Model Performance on Healthy Loans.
        * Precision 100%, showing that of the loans the model predicted as healthy, all of them were actually healthy
        * Recall 99%, which means that only 1% of the actual healthy loans wasn't predicted by the model.
    * Model Performance on High-Risk Loans
        *  Precision 85%, meaning of the loans that were predicted as high-risk, 15% were actually healthy,
        *  Recall 91%, which shows that out of all of the high-risk loans, 9% weren't predicted by the model. 


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
