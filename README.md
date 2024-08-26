# credit-risk-classification


## Overview of the Analysis

* This analysis was to determine the accuracy of the banking institutions system for determing if candidates are good options for a loan. The ranking places candidates in either a "0" for good standing or "1" for likely to default. The variables used to determine the candidates examine their current standing loans and the amount of debt. It also looked at their current income and the ratio to debt.  

* The model is trying to predict, if the candidate took out another loan, would they be able to pay it back in a timely manner.


* Describe the stages of the machine learning process you went through as part of this analysis.
The machine learning process takes a section of the data as "training data" meaning the model uses this set of data learn trends, patterns and use that information to then create a "test data" group. And make predictions based off those two sets.

* Logistic regression is a model used for binary classification problems, where the outcome is categorical and typically takes on two possible values (e.g., 0 or 1, true or false, yes or no). Unlike linear regression, which predicts continuous values, logistic regression predicts the probability of a certain class or event occurring.

## Results

It appears that the model does a great job of predicting the "0" healthy loan, showing high 90s in accuracy. However, the model has a much lower ability in the accuracy of which they predict those that are "high-risk." It is clear they need to work on their "high-risk" model, either by changing parameters, increasing data, etc. They may be overlooking potential candidates and incorrectly flagging them as "high-risk.
* Machine Learning Model 1:
              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.94      0.89       619

    accuracy                           0.99     19384
   macro avg       0.92      0.97      0.94     19384
weighted avg       0.99      0.99      0.99     19384




## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

It appears the training model did better, but only slightly. Both models were not too accurate in assessing the "high risk" candidates.
* I think it is more important to be able to accurately assess the "1" or high-risk, because we could be missing out on candidates who do qualify and could need the loan. 

I think both models need more data to accurately and confidently assess the "high-risk" candidates. 

## Support
I reference the scikit learn website (https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html) to complete this project and the in class activities. 
