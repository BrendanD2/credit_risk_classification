# Credit Risk Classification Report

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of this analysis is to train the given lenders data based on the features using a logistic regression to predict whether a loan would be healthy or risky. 
* The data used was a given data set with the following features: loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, and total debt. These features were trained and tested to help predict the loan status (0 or 1). 0 is a healthy loan and 1 is an unhealthy loan.
* I then trained and tested the data and used a logistic regression to make predictions using the testing data and fitting the model using the training data.
  
## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
    * The model had an accuracy of 99%. When predicting a loan status of 0 (healthy) the precision was 100% with a recall of 99%. When predicting a loan status of 1 (unhealthy) the precision was 84% with a recall of 94%. When predicting true positives and negatives the model was fairly accurate based on the recall values. 

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* The model was able to perform best with true/false positives. The model based on the confusion matrix recorded the most true positives with a small amount of false positives. This means that the model was highly accurate when predicting healthy loans which will be very useful to users. The smallest amount predicted was false positives which is good, but for this problem we would want that number to be as close to 0 as possible. There was a higher amount of false negatives which can also be just as hurtful as the false positives because people can be missing out on healthy loans because of the prediction. 
* In this problem it is important to predict both '1' and '0' because incorrectly predicting a healthy loan when it is unhealthy can hurt the user. 

