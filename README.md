# Credit_Risk_Analysis

## Overview of Project
### Purpose

A lending services provider, Fast Lending, wants to use machine learning to quickly categorize loan applicants as high or low risk loan candidates. The more accurate the predictions of the machine learning model are, the lower the loan default rates will be.

Since credit risk is an unbalanced classification problem, several different machine learning models will be tested. The different modeling approaches tested will be oversampling, undersampling, combination, and decision tress. By comparing the performance metrics of each model - accuracy percentage, precision score, and recall scores – a recommendation for which specific modeling approach Fast Lending should utilized will be delivered. 

## Analysis Results 

The performance metrics for each model are below:

Naïve Random Oversampling:

<img src ="https://github.com/Jafranco96/Credit_Risk_Analysis/blob/main/Resource/Oversampling.PNG">

This model had an accuracy of 62%, an overall precision rate of 99%, and an overall recall rate of 66%.

SMOTE Oversampling:

<img src ="https://github.com/Jafranco96/Credit_Risk_Analysis/blob/main/Resource/SMOTE%20Oversampling.PNG">

This model had an accuracy of 63%, an overall precision rate of 99%, and an overall recall rate of 64%.

Undersampling:

<img src ="https://github.com/Jafranco96/Credit_Risk_Analysis/blob/main/Resource/Undersampling.PNG">

This model had an accuracy of 59%, an overall precision rate of 99%, and an overall recall rate of 57%.

Combination:

<img src ="https://github.com/Jafranco96/Credit_Risk_Analysis/blob/main/Resource/Combination.PNG">

This model had an accuracy of 63%, an overall precision rate of 99%, and an overall recall rate of 57%.

Balanced Random Forest:

<img src ="https://github.com/Jafranco96/Credit_Risk_Analysis/blob/main/Resource/Balanced%20Random%20Forest%20Classifier.PNG">

This model had an accuracy of 80%, an overall precision rate of 99%, and an overall recall rate of 90%.

Easy Ensemble AdaBoost Forest:

<img src ="https://github.com/Jafranco96/Credit_Risk_Analysis/blob/main/Resource/Easy%20Ensemble%20Classifier.PNG">

This model had an accuracy of 79%, an overall precision rate of 99%, and an overall recall rate of 90%.

## Analysis Results Summary

The performance comparisons detail a clear distinction between the sampling and random forest models. Not only do the random forest models have about a 20% higher accuracy score, they also have an increase of about 30% in the recall scores. It is imperative that the machine learning model minimizes the number of high risks loans that it incorrectly categorizes as low risk to as low possible. This is why the recall score is so crucial to consider and why the accuracy percentage can not be the only consideration when choosing which model to move forward with.

Due to extremely high percentages for both accuracy and recall, Easy Lending should utilize one of the two random forest models. The official recommendation will be to use the balanced random forest model since it has a slightly higher accuracy than the easy ensemble model. Using this model, Easy Model will be able to quickly categorize future loan applicants and minimize the instances of misclassification.
