Customer Churn Prediction System 

Customer Churn Prediction is a machine learning project that helps businesses identify customers who are likely to stop using a service.

By predicting churn early, companies can take steps to retain customers, improve customer satisfaction, and reduce revenue loss.

This project applies multiple machine learning models to customer data and compares their performance to select the best model.

Dataset Description

File: Telco-Customer-Churn.csv

The dataset includes customer details such as:

Gender

Senior Citizen

Partner & Dependents

Tenure

Monthly Charges

Total Charges

Contract Type

Payment Method

Internet Service

Churn (Target Variable)

Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

XGBoost

Jupyter Notebook

 Machine Learning Workflow

Data Loading and Cleaning

Exploratory Data Analysis (EDA)

Feature Encoding

Train-Test Split

Model Training

Model Comparison

Model Evaluation

Final Prediction

 Machine Learning Models Used

Decision Tree Classifier

Random Forest Classifier

XGBoost Classifier

 Model Performance & Results

All three models were trained and evaluated using the same dataset.

Model	Performance
Decision Tree	Moderate accuracy
XGBoost	High accuracy
Random Forest	Best performance

 Random Forest achieved the highest accuracy and better generalization, making it the final selected model for churn prediction.

 Best Model: Random Forest

Reasons for selecting Random Forest:

Higher accuracy compared to other models

Reduced overfitting

Better handling of feature importance

Stable performance on unseen data
