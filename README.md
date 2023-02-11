# Fraud Detection

![1674286847076](https://user-images.githubusercontent.com/90085137/213849272-61c50dcf-8ffa-4bf5-931c-d00fb7615b5d.png)

## Methodology
Tool: Jupyter Notebook, Google Colab <br>
File Type: .csv <br>
Language: Python <br>
Packages: sklearn, numpy, pandas, matplotlib.pyplot  <br>
Method and Techniques: Oversampling, Logistic Regression, Decision Tree, Random Forest, xgBoost, ROC Curve, Confusion Matrix <br>

## Available Data
~ 1 million transaction records

## The Objective
The Chief Technology Officer of Broom Solutions, Glinda Broom, has requested your team find the reason for reducetion in revenue. 

## Problem Identified
Reduction in Revenue;

Caused By

Reduction in Transaction;

Caused By

Reducrion in Customers;

Found By

Customer feedback

__1. Too Good at Fraud Detection:__
Broom Solutions current fraud system catches 98% of fraudulent transactions.

__2. Flagging the innocent:__
Non fraudulent transactions flagged as fraud 6% of the time.

__3. Client Complaints:__
Retail and ecommerce clients complain of losing long term business from customer frustration. 

## Conclusion
Precision is more important in this case, where False Alarms (False Positives), are more costly than Overlooked Cases (False Negatives). Although we allow more fraud transcation to go through at lower value, we do want less fraud to go through at higher value. Therefore, we developed an innovative solution with a dual model system:

__Case 1: When transaction amount <$600:__ 

&emsp; Allow __more__ trasctions to improve cusomer satisfaction (Higher Precision to minimize false flagged transactions)


__Case 2: When transaction amount >=$600:__

&emsp; Allow __less__ fraud trasctions to reduce money loss (Higher Recall to reduce fraud transaction)

## Future Work
Apply A/B testing to understand the performance of the new approach.
