# Module 12 Report 

## Overview of the Analysis

This repository employs a logistic regression model from the Scikit-learn library to predict loan risk based on historical lending data. The model is trained on 80% of the data, using features such as the borrower's debt, income, and derogatory marks to assess loan risk, categorized as either healthy or high risk. The remaining 20% of the data is used to evaluate the model's performance by comparing predicted loan outcomes with actual results. The goal of this model is to help the loan company better assess the potential risks of loans, enabling more informed decision-making.


## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Logistic Regression Machine Learning Model:
    * Model Performance on Healthy Loans.
        * Precision 100%:
           *  Out of the loans predicted by the model as healthy, all of them were actually healthy
        * Recall 99%:
           * This means that only 1% of the actual healthy loans wasn not predicted by the model.
    * Model Performance on High-Risk Loans
        *  Precision 85%:
           *  Meaning of the loans that were predicted as high-risk, 15% were actually healthy,
        *  Recall 91%:
           *  Out of all of the high-risk loans, 9% weren't predicted correctly by the model.
     *  Overall accuracy 99%:
        *  Out of all of the predictions, only 1% wasn't correct. However, this metric is slightly skewed as there was more healthy loans, which the model       performed better on than high risk loans.
        
## Summary

Overall, this machine learning model performed well in determining the risk level of a loan based on historical loan data. The model was particularly effective at predicting healthy loans, achieving near-perfect accuracy on the test data. This suggests that the model could be a valuable tool for the company in identifying low-risk, healthy investments. However, while the model's predictions for high-risk loans were good, they were not as accurate, with a tendency to misclassify some high-risk loans as healthy. This indicates that there is still room for improvement in the model's ability to identify high-risk loans before it can be fully utilized by the company.

It is important to note that while predicting the healthiness of a loan is beneficial, errors in predicting high-risk loans would be much more costly to the business. Misclassifying a high-risk loan as healthy could lead to significant financial damage, far outweighing the impact of not approving a healthy loan. Therefore, the flaws in this model's predictions of high-risk loans could potentially outweigh its strengths for the company. Consequently, I would not recommend using this model until its performance in predicting high-risk loans is improved. Although 85% precision is still good, misclassifying 15 out of every 100 high-risk loans could accumulate and have a substantial negative financial impact on the business.


