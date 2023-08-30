# Module 20 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

We performed supervised learning on data about loans from a peer-to-peer lending services company. The intention of the analysis was to see if we could use certain features in the data (namely the loan size, the interest rate, the borrower income, the debt to income ratio, the number of accounts, and the derogatory marks) to predict whether the loans of the users would be healthy or high risk. The reason to do this analysis is to try to use these features to predict whether a new customer interested in a loan is at high risk of defaulting or not. In our data, we had 75036 healthy loans and 2500 high risk loans. The overall steps that I completed to do this analysis were to separate the labels (0 or 1) from the features, split the data into testing and training data, create a classifier, fit the classifier, save the predictions, then create metrics, such as balanced accuracy score, recall, precision, as well as the confusion matrix. The classifier was a logistic regression model.

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
The logistic regression model that I created has a balanced accuracy score of 0.952, a precision score of 0.847, and a recall score of 0.910.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

I recommend using the logistic model that I created because it has a quite high balanced accuracy score at 95%. It does a great job at predicting healthy loans, which a precision of 1.00 and a recall of 0.99. It does slightly worse at predicting the high risk loans, with a precision of 0.85 and a recall of 0.91. I would argue that it is more important to predict the high risk loans, so there is definitely room for improvement, but I still feel like the numbers are high enough to warrant the use of this model.


