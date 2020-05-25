# Customer-Churn-ML
Background : The dataset is related to a telecommunication provider and its customers. The customers leaving this provider aka "churn rate" is high and hence the provider wants to predict which of its customers would leave the provider in future.  

Aim: The objective is to predict whether a customer will change telecommunications provider or not.

Details:
It is a binary classification problem with imbalanced data set with 86% of 'No' (Customers who did not leave the provider) and 14%  - 'Yes'

1. Evaluation Metric Choosen : f1 score
2. Cost-sensitive models and used data sampling algorithms like SMOTE are used to account for imbalance in data 
3. Various ensembling methods like Random forest, Extra trees, Gradient Boosting etc., are used to see if the prediction score increases
