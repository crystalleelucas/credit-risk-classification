# Overview of the Analysis

The goal of this study is to see how well two computer models can predict whether a loan is risky or not by looking at financial informationm, using data about loan size, interest rates, borrower income, and other factors in order to determine if a loan is safe (0) or risky (1).

To begin, our data is divided into two parts for training and testing. I made one model with the original data and checked how well it worked, measuring the model's accuracy, precision, and recall. To handle an imbalance in the data, more examples were added using a technique called RandomOverSampler. Then, I created another model with the new, balanced data and checked how well it worked using the same measurements above.

* two methods in this study: LogisticRegression and RandomOverSampler.

## Results

Machine Leanrning Model 1 with original data:

* Accuracy: The model is very accurate, correctly classifying 99% of cases.
* Precision for healthy loans (0): Excellent at identifying true positives with very few mistakes.
* Precision for high-risk loans (1): Moderately effective in spotting high-risk loans with some errors.
* Recall for healthy loans (0): Correctly identifies nearly all healthy loans with little misses.
* Recall for high-risk loans (1): Effective at identifying high-risk loans with some misses.


Machine Learning Model 2 with Resampled Data:

* Accuracy: The model is also very accurate, correctly classifying 94% of cases.
* Precision for healthy loans (0): Moderatley effective at identifying true positives with very few mistakes.
* Precision for high-risk loans (1): Very effective in spotting high-risk loans with very few mistakes.
* Recall for healthy loans (0): Correctly identifies nearly all healthy loans with very few misses.
* Recall for high-risk loans (1): Very effective at identifying high-risk loans with very few misses.\

### Summary

Module 2 outperforms Module 1 trained with original data, particularly with high-risk(1) loans.
This would be benefiical for fianicial institutions to reduce risks and loss. 
