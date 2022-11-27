# Model Card

## Model Description

**Input:** 
The following dataset used consists of the following inputs:
1. 4 categorial attributes, ie. Geography, Gender, a Credit Card Owned Indicator, as well as the Active Status of the Customer.
2. 8 continuous attributes, ie. Customer ID, Surname, Credit Score, Age, Tenure with the Bank, Bank Balance, Number of Bank Products, as well as the estimated salary.

**Output:** 
The following dataset used consists of 1 categorical output used for prediction, ie. Exited Status of Customer. 1 indicates the actual churned status of our bank customer, while 0 indicates that the bank customer is still retained in the business.

**Model Architecture:** 
Based on the following model performance, we will be selecting the Random Forest Classifier as our model fitting. We note that this technique is deemed the best model that gives a decent balance of the recall and precision. Based on our scores, Random Forest provided a precision of 91%, and recall of 56% of customers that do actually churn.

## Performance
The following table shows the summary table of our model performance on predicting the test dataset. The metrics used for checking the model performance includes, precision, recall and accuracy. The data we are analysing on includes the classified churned status of the bank customer, ie. 0 or 1. In the end, we find our accuracy rate of predicting is high at 86%. However, it still misses about half of those that end up churning. Nevertheless, we have a high precision rate of 72% on predicting customers that actually churned.

              precision    recall  f1-score   support

           0       0.88      0.96      0.92      1610
           1       0.72      0.45      0.55       390

    accuracy                           0.86      2000
   macro avg       0.80      0.70      0.73      2000
weighted avg       0.85      0.86      0.84      2000


## Limitations
Based on the displayed results, we find this model to have an extremely poor results on the recall of our actual churned customers, at only 45%. Furthermore, with the case of using the Random Forest Classifier, there might be a possibility of overfitting our model. 

## Trade-offs
We note that given the use of the Random Forest Classifier, there is a tradeoff between the training time (and space) and increased number of trees employed in the model, that ensures greater accuracy in our prediction. This might therefore impact the model performance that we have. 