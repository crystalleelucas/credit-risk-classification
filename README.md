#Overview of the Analysis

The goal of this study is to see how well two computer models can predict whether a loan is risky or not by looking at financial information. I used data about loan size, interest rates, borrower income, and other factors in order to determine if a loan is safe (0) or risky (1).

To begin, our data is divided into two parts for training and testing. I made one model with the original data and checked how well it worked, measuring the model's accuracy, precision, and recall. To handle an imbalance in the data, more examples were added using a technique called RandomOverSampler. Then, we created another model with the new, balanced data and checked how well it worked using the same measurements above.

 two methods in this study: LogisticRegression and RandomOverSampler.
