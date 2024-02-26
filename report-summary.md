# Module 20 - Credit Risk Classification

## Overview of the Analysis

The purpose of this analysis was to use a dataset of historical lending activity to see if we can predict if a loan is low or high-risk. 

The data used was contained in a csv file that had various information about the loan and borrower. Using this data a supervised machine learning model was built to see if we could accurately predict what category the loan would fall in to.  

To perform this analysis a supervised machine learning model was built. This was done by:

* Separating the data in to labels and features, with the loan status of healthy or high-risk being the label and the other columns of data   as features.
* Splitting the data in to training and testing sets.
* Creating a logistic regression model as we are classifying loans as only two options. 
* Fitting the model with the training data.* Making predictions with the test data and evaluating the predictions with the test labels.



## Results

 
#Accuracy 

* 0.99185


#Precision 

* Healthy: 1.00
* High-Risk: 0.85

#Recall 

* Healthy: 0.99
* High-Risk: 0.91

  
  

## Summary


The model does a good job at predicting healthy loans. However it classifies quite a high percentage of high-risk loans incorrectly as healthy. That said there are very few high-risk loans for the model to learn from when compared to the number of healthy loans in the data set. If there were more of these types of loans the model may be improved.
For trying to classify loans, trying to prevent high-risk loans is more important than giving out a loan as more money can be lost from a single loan that defaults than the interest earned from a loan.




