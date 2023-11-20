# Overview of the Analysis

The purpose of this study is to see how well two computer models can predict whether a loan is risky or not by looking at financial information, using data about loan size, interest rates, borrower income, and other factors in order to determine if a loan is safe (0) or risky (1).

The data is divided into two parts for training and testing. I made one model with the original data, measuring the model's accuracy, precision, and recall. More examples were added using a technique called RandomOverSampler due to imbalances. Then, I created another model with the new, balanced data and checked how well it worked using the same measurements above. I used two methods in this study: LogisticRegression and RandomOverSampler.

## Results

* Machine Leanrning Model 1 with original data:

Precision: 100% accuracy predicting healthy loans, 87% accuracy predicting high-risk loans
Accuracy: 94% balanced accuracy score
Recall: 100% recall for healthy loans, 89% recall for high-risk loans

* Machine Learning Model 2 with Resampled Data:

Precision: 100% accuracy predicting healthy loans, 87% accuracy predicting high-risk loans
Accuracy: 99% balanced accuracy score
Recall: 100% recall for healthy loans, 100% recall for high-risk loans

## Summary

Module 2 with balanced resampled data outperforms Module 1, particularly with high-risk(1) loans, therefore I recommened using Model 2.
This would be benefiical for fianicial institutions to reduce risks and loss when trying to determine approval or rejection for loans. 
