# credit-risk-classification

Overview of the Analysis

This repository used a dataset of historical lending activity from a peer-to-peer lending services company which built two models to predict the creditworthiness of future borrowers to help banks and lending companies to decide better and lower the risk of losing their income. The dataset provided by the bank has more than 77000 entries with indicators such as loan size, interest rate of the loan, borrower's income, etc. Two Logistic Regression models were used that estimate the probability of an event occurring based on a given dataset of independent variables which in our case is the status of a loan. Feeding the training data into the machine, the test data was compared to see how well the model predicts the events needed. There were 75036 non-defaults and 2500 defaults meaning the dataset is not balanced. Using Oversampling method, a model was created that better predicts those that might default on their loan. 

Results

Balanced accuracy, Precision and Recall scores

Accuracy Score shows how often the model was correct.

Precision Score measures confidence that the model correctly made the predictions.

Recall Score indicates the number of actual default transactions that the model correctly classified as default.

Machine Learning Model 1 (Trained using the original data) :
Balanced Accuracy Score : 0.9520479254722232 which means this model is 95% accurate.
Precision Scores :
Healthy Loans : 1 (100% precise)
High Risk Loans : 0.85 (85% precise)
Recall Scores :
Healthy Loans : 0.99 (99% correct)
High Risk Loans : 0.91 (91% correct)
Machine Learning Model 2 (Trained using the oversampled data) :

Balanced Accuracy Score : 0.9936781215845847 which means this model is 99% accurate.
Precision Scores :
Healthy Loans : 1 (100% precise)
High Risk Loans : 0.84 (84% precise)
Recall Scores :
Healthy Loans : 0.99 (99% correct)
High Risk Loans : 0.99 (99% correct)

Summary

Oversampling method allowed the model to better predict if a loan was going to default or not. It increased the accuracy and the recall score significantly. Overall, both models did a great job at having over 95% accuracy and above 90% Recall. In this case we are attempting to reduce our defaults, so using oversampling to reduce that possibility makes most sense. In this case, it is more important to predict the high risk loan than the healthy loan. 
