# Credit Card Fraud Detection Model

## Introduction:

It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.
in that perspective , to automate and speedify the task , this model will as a best resource for them.

## About Dataset

The dataset contains transactions made by credit cards in September 2013 by European cardholders.<br>
It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

## Working

As model is currently trained on Nueral Network ,it will gets activated when a new transaction will be occurred , and model will scan according to its trained data.<br>
If transaction is find to be outlier , it will be count as a Fraud Transaction.

## Tech Stack

- Supervised Machine Learning
- Logistic Regression
- Artificial Neural Network

## Future Scope

We can train the model for more ways , like Random Forest (Ensemble Learning) , 7 types of SVM (Binary Classification) and many more. 

## Conclusion

This model will work best for detecting fraud transaction from given data done by Credit Card.

