# creditcardFraudDetection
This project is to do analysis on traditional and modern deep learning models to detect fraud credit card transactions.

#Abstract
Credit cards are one of the most popular forms of payment for both online and in-store purchases. Because of its popularity, the cases of fraud associated with it are also increasing and so detecting fraud transactions has become essential for the credit card issuing companies to minimize their losses and for the customers to avoid monetary losses. The traditional methods of manual detection of fraud are time-consuming and inefficient and thus artificial intelligence methods like data mining come into the picture. In this project, our goal is to build a fraud detection system for credit cards using different machine learning algorithms and techniques. This would help us find an efficient detection system by comparing the performances of the different AI models used in this project.

#Motivation:
The need for the fraud detection system is significant for both the cardholders and the credit card companies. Fraud transactions force credit card companies to give replacement cards, customer support for the users and can cause damage to their reputation. With the cost of these steps rising and declining cardholder’s trust, it becomes necessary for them to predict and detect the fraud at the time of the transaction itself.
Data Set:
The data set for this project is collected by ULB Machine Learning Group and it has the credit card transactions of the European cardholders for the month of September in 2013. This data set is highly unbalanced, the positive class of fraud accounts for 0.172% of all transactions. And most of the features are not disclosed because of the confidentiality of the cardholders. The data set is available in the link below: https://datahub.io/machine-learning/creditcard#resource-creditcard_zip
 
#Background:
There have been many studies to find an efficient fraud detection system for credit cards in the field of artificial intelligence. Most of the studies have utilized only the traditional models of machine learning and we have considered such two IEEE papers as our references for this project.
Links:
https://ieeexplore-ieee-org.proxy.lib.csus.edu/document/8123782 : “Credit card fraud detection using machine learning techniques: A comparative analysis” https://ieeexplore-ieee-org.proxy.lib.csus.edu/document/7972424 : “Analysis on credit card fraud identification techniques based on KNN and outlier detection”

#System/Algorithmic Design:
Using Convolutional Neural Network (CNN), Long Short-Term Memory (LSTM) to predict fraudulent transactions and comparing its performance with traditional ML models like k-nearest neighbors (KNN), Logistic Regression (LR) and Support Vector Machine (SVM). There have been papers published previously which compare Naïve Bayes, k-Nearest Neighbour, Logistic Regression. The links to the mentioned papers are given in the background section. We plan to yield a better result by tuning the hyperparameters.

#Evaluation Plan:
Metrics like precision, accuracy, F1 score, recall, Matthews correlation coefficient, confusion matrix, and ROC curve will be used for the analysis of various models and for evaluating models that achieve high accuracy. Since the dataset is highly unbalanced, we would need to balance the data, finding outliers, and then splitting the data in the ratio 80% train and 20% test. The features V1 - V28 are kept confidential have already been normalized. The amount feature would need to be normalized.
