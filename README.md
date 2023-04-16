# Credit_Card_Fraud_Detection

Credit Card Fraud Detection
This project aims to detect credit card fraud using a logistic regression model. The dataset used in this project contains hidden features of credit card transactions, and the target is to identify fraudulent transactions.

Table of Contents
Introduction
Data
Data Preprocessing
Model Training
Results
Conclusion

Introduction
Credit card fraud is a major concern for financial institutions and their customers. This project aims to detect fraudulent transactions using a logistic regression model. The dataset used in this project contains hidden features of credit card transactions, and the target is to identify fraudulent transactions.

Data
The dataset used in this project contains credit card transaction data with hidden features. The dataset is imbalanced, with the minority class representing less than 1% of the total data. The dataset was cleaned and no null values were present.

Data Preprocessing
The dataset was preprocessed by splitting it into training and testing sets. The imbalanced nature of the dataset was handled by upsampling and then downsampling the minority class to balance the dataset. The dataset was then scaled using StandardScaler to ensure that all features were on the same scale and to improve the performance of the model.

Model Training
The logistic regression model was trained on the preprocessed data using scikit-learn. The model was trained on the training dataset and evaluated on the testing dataset using the Area Under the ROC Curve (AUC) score.

Results
The logistic regression model achieved an accuraccy of 91% on the testing dataset using upsampling to handle the imbalance. The results indicate that the model can accurately detect fraudulent transactions.

Conclusion
This project demonstrates the use of logistic regression in detecting credit card fraud. The model achieved good results on the testing dataset, indicating that it can be used to make accurate predictions.
