# Prevention of Bank Customer Churn: A Predictive and Analysis Model

## NON-TECHNICAL EXPLANATION OF YOUR PROJECT
With now a greater concern of optimising revenue and profit in banks, the study of customer churn prediction is vital in the operations for the banking industry. Stakeholders find this crucial for decision making given the lower cost of retaining rather than acquiring new customers. his is the metric that determines the success or failure of a business. Successful customer retention is also known to increase the customer’s average lifetime value, making all future sales more valuable and improving unit margins.

The following project focuses on achieving a few key goals of building a prediction model, including:
1. Classification the churn status of bank customers.
2. Attaching a probability of churn for bank customers.
3. Selection of the best model performance used to fit our training dataset of bank customers, using the techniques of Logistic, SVM and Random Forest Classifier.

## DATA
The following dataset used consists of the following:
1. 1 categorial output, ie. Exited Indicator of Customer
2. 4 categorial attributes, ie. Geography, Gender, a Credit Card Owned Indicator, as well as the Active Status of the Customer.
3. 8 continuous attributes, ie. Customer ID, Surname, Credit Score, Age, Tenure with the Bank, Bank Balance, Number of Bank Products, as well as the estimated salary.

Pl note that the following dataset is sourced on Kaggle from the following link:
https://www.kaggle.com/datasets/adammaus/predicting-churn-for-bank-customers

## MODEL 
Based on the following model performance, we will be selecting the Random Forest Classifier as our model fitting. We note that this technique is deemed the best model that gives a decent balance of the recall and precision. Based on our scores, Random Forest provided a precision of 91%, and recall of 56% of customers that do actually churn.

## HYPERPARAMETER OPTIMSATION
Given the model we used is Random Forest Classifier, I note on the hyperparameters we will considering to optimise for. This includes:
1. Maximum Depth
2. Maximum Features
3. Number of Estimators
4. Minimum Spilt of Samples

The following hyperparameters are optimised and tuned using the Grid Search Techique.

## RESULTS
Based on the results from predicting usng our test dataset, we find our accuracy rate of predicting is high at 86%. However, it still misses about half of those that end up churning. Nevertheless, we have a high precision rate of 72% on predicting customers that actually churned.
