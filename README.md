Project Title: Predicting Bank Term Deposit Subscriptions Using Decision Tree Models
Overview
This project leverages decision tree models to predict whether a bank client will subscribe to a term deposit based on various demographic and account-related features. The dataset, consisting of 45,211 observations, includes factors such as age, job type, marital status, loan status, and previous campaign outcomes. By applying multiple decision tree models with different criteria and depth limitations, we aim to identify patterns that can help the bank improve its marketing campaign strategies.

Objectives
Predict Subscription Outcome: Use demographic and behavioral attributes to predict whether a client will subscribe to a term deposit.
Evaluate Model Performance: Compare various decision tree models (entropy and Gini criteria) with and without depth limitations to optimize predictive accuracy and interpretability.
Address Class Imbalance: Evaluate performance metrics for both subscribed and non-subscribed clients to highlight any issues with class imbalance.
Dataset
Source: Bank Marketing Dataset from the UCI Machine Learning Repository.
Features: 17 columns, including age, job, marital status, education, balance, housing loan, contact type, and the target variable y (subscribed or not).
Model Summary
Four decision tree models were built and evaluated:

Model 1: Entropy criterion, no max depth.
Model 2: Gini criterion, no max depth.
Model 3: Entropy criterion, max depth of 3.
Model 4: Gini criterion, max depth of 3.
Performance Metrics: Each model was assessed based on accuracy, balanced accuracy, precision, and recall to measure its ability to handle class imbalance and provide meaningful predictions.

Key Results
All models achieved high overall accuracy (~88-90%), but models with limited depth showed better interpretability and precision for the minority class (subscribed).
Models struggled with class imbalance, as reflected in lower balanced accuracy scores. Future work could include techniques like SMOTE or adjusting class weights to improve minority class predictions.
Conclusion
This project demonstrates the potential of decision tree models for predictive analytics in banking. While high accuracy was achieved, future improvements are needed to handle class imbalance more effectively. A model with a depth limitation may offer a balance between interpretability and performance, making it a feasible choice for real-world deployment.
 
