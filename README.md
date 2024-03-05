E-Commerce Customer Churn Prediction

This project aims to predict customer churn for an e-commerce company using machine learning techniques. By identifying factors influencing churn and implementing preventive measures, the company can improve customer retention and business performance.

Table of Contents
Introduction
Dataset
Exploratory Data Analysis
Classification Model
Results
Conclusion
Dependencies

Introduction
Customer churn, also known as customer attrition, refers to the loss of customers or subscribers. In the context of e-commerce, understanding and predicting churn is crucial for retaining customers and maximizing revenue. This project utilizes machine learning techniques to analyze customer data and predict churn, allowing the company to take proactive measures to prevent it.

Dataset
The dataset used in this project contains information about customers, including demographics, purchasing behavior, and satisfaction scores. It consists of 5630 rows and 20 columns, with variables such as CustomerID, Churn, Tenure, PreferredLoginDevice, etc.

Exploratory Data Analysis
Exploratory Data Analysis (EDA) was conducted to understand the characteristics of the dataset and identify potential factors influencing churn. Key steps in EDA include:

Descriptive statistics
Visualization of target variable distribution
Correlation analysis
Exploration of categorical and numerical variables
Feature engineering
Classification Model
A random forest classifier was chosen to build the prediction model due to its robustness and ability to handle complex relationships in the data. The following steps were performed:

Data preprocessing: One-hot encoding for categorical variables, scaling for numerical variables, and splitting into training and testing sets.
Model training: Training the random forest classifier on the training data.
Model evaluation: Evaluating the model's performance on the testing data using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
Feature importance analysis: Analyzing feature importance to understand factors influencing churn prediction.
Results
The trained model achieved [accuracy(0.96)/precision(0.96)/recall(0.96)/F1-score(0.96)/ROC-AUC score(0.86)] on the testing data, indicating its effectiveness in predicting customer churn. Key factors influencing churn include [Tenure,WharehoueToHome,CashbackAmmount]. Based on these insights, actionable strategies can be devised to prevent churn and improve customer retention.

Conclusion
In conclusion, this project demonstrates the application of machine learning techniques to predict customer churn in the e-commerce domain. By understanding the factors influencing churn and taking proactive measures, the company can enhance customer satisfaction, loyalty, and business profitability.

Dependencies
Python 3
pandas
scikit-learn
matplotlib
seaborn
