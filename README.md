# Customer_Churn_Prediction
This project's objective is to forecast customer churn for a telecom company.
This dataset is valuable for analyzing customer behavior and developing strategies to reduce churn and improve customer retention.


## Problem Description; what is customer churn?
In the competitive telecommunications industry, understanding customer behavior is crucial for staying ahead in the competition.


Customer churn means when a customer decides to stop using a company's services. Businesses often study customer churn analysis  since it is helpful for a company if they learn which customers are about to leave.

## Data Description

This dataset provides comprehensive information on customer churn, services, account details, and demographic data. It includes:

- **Churn**: A binary column denoting whether customers left ('Yes') or stayed ('No') within the last month.
- **Services**: Information on services signed up for, such as phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies.
- **Customer Account Info**: Details about customer tenure, contract type, payment method, paperless billing, monthly charges, and total charges.
- **Demographics**: Demographic data, including gender, age range, and whether customers have partners and dependents.

## Objectives

To gain a deeper comprehension of the data and provide our analysis with a clear focus, we can formulate some fundamental questions:

1. How does the length of a customer's tenure with the company influence their likelihood of churning?

2. Is there a correlation between churn and factors such as monthly charges and total charges?

3. What is the connection between gender, partner status, and churn?

4. Does the availability of technical support play a role in influencing customer churn?

5. Which aspect of the contract has the most significant impact on the business?

6. How does the quality of service differ for customers who have opted for streaming services?

7. Given that the dataset pertains to the telecom industry, what insights can we uncover regarding phone and internet services?

## Steps

- Problem Understanding: Gain a clear understanding of the telecom churn prediction problem.


- EDA: Utilize various visualization techniques to familiarize yourself with the data, uncover patterns, and analyze features.


- Data Split: Divide the dataset into training and testing sets.


- Feature Engineering: Transform categorical features into numerical representations and standardize the features.


- Model Training: Train supervised learning models like SVM, Random Forest, and XGBoost on the training data and evaluate their performance on the test data.


- Summary: Summarize the project's findings and outcomes.


## Model Building

- I selected four machine learning models, Logistic Regression, Random Forest, K-Nearest Neighbors (KNN) and Gradient Boosting, for predicting customer churn. These models were chosen for their ability to effectively handle a wide range of data types, including both continuous and categorical variables.
