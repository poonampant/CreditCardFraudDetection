# Credit Card Fraud Detection in Python
This repository contains Credit card fraud detection algorithm using machine learning techniques in python.


Credit Card Fraud Detection : With a lot of people, banks and online retailer being a victim of credit card fraud, a model detecting whether the transaction is fraudulent or not and can help in saving a huge amount of money.


Dataset : The dataset has been obtained from kaggle. This dataset contains 284807 rows and 31  columns .Out of 31 columns  one is class column ie target column that specifies whether the transaction is fraudulent or not.If class is 1 then fraud else not a fraud transaction. 

Preprocessing : check whether the data contains any null values or not.Correlation has been  used to find relevant features .

Algorithm : As it is a Classification Problem .The algorithm used is Logestic Regression and Random Forest Classifier.For both algorithm confusion matrix is made and their accuracy is being compared. Random Forest Classifier is more accurate than Logistic Regression  in predicting the transaction is fraudlent or not.

Visualisation : The library used for visualizing the data, confusion matrix etc. is seaborn  and tool used for visualizing the data is Tableau for making various graph.

This code is prepared using Jupyter Notebook.

You can find the dataset in the link provided below: https://www.kaggle.com/mlg-ulb/creditcardfraud
