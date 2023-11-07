## Customer_Churn_Prediction

## **Introduction**
This project aims to forecast customer churn for a telecom company. Customer churn prediction is crucial for businesses in the competitive telecommunications industry as it helps them understand and retain their customers, ultimately leading to increased revenue and customer satisfaction.

## **Problem Description**
Customer churn, in this context, refers to when a customer decides to stop using a company's services. Analyzing customer churn is valuable for identifying customers at risk of leaving.

## **Data Description**
The dataset provides comprehensive information on customer churn, services, account details, and demographic data, including:

- Churn: A binary column indicating whether customers left ('Yes') or stayed ('No') within the last month.
- Services: Information about services signed up for, such as phone, multiple lines, internet, and more.
- Customer Account Info: Details about customer tenure, contract type, payment method, and more.
- Demographics: Information including gender, age range, and partner and dependent status.

## **Objectives**
To guide our analysis, we have defined the following objectives:

1. Investigate the impact of customer tenure on churn.
2. Explore correlations between churn and factors like monthly charges and total charges.
3. Analyze the relationship between gender, partner status, and churn.
4. Examine the influence of technical support on customer churn.
5. Identify the most significant contract-related factors affecting churn.
6. Assess the quality of service for customers with streaming services.
7. Uncover insights related to phone and internet services in the telecom industry.

## **Steps**
1. **Problem Understanding**: Gain a clear understanding of the telecom churn prediction problem.
2. **EDA**: Explore the data through data cleaning, data visualization, and feature analysis.
3. **Data Split**: Divide the dataset into training and testing sets.
4. **Feature Engineering**: Transform categorical features into numerical representations and standardize the features.
5. **Model Training**: Train supervised learning models including Logistic Regression, Support Vector Machine, XGBoost, and Neural Network (Feedforward NN) on the training data.
6. **Summary**: Summarize the project's findings and outcomes.

## **Model Building**
We have chosen the following models for churn prediction, each serving specific purposes:

1. **Logistic Regression**:
   - Model: Simple linear model for binary classification.
   - Reason: It is interpretable, suitable for categorical features, and serves as a baseline model.

2. **Support Vector Machine (SVM)**:
   - Model: Effective for capturing complex decision boundaries.
   - Reason: SVM can handle both categorical and numerical features and is capable of using kernel tricks for feature mapping.

3. **XGBoost**:
   - Model: Ensemble model with high predictive performance.
   - Reason: XGBoost excels at handling categorical data with one-hot encoding and capturing complex relationships.

4. **Neural Network (Feedforward NN)**:
   - Model: Deep learning model for capturing non-linear patterns.
   - Reason: Suitable for high-dimensional data, excels in handling intricate relationships.

## **Conclusion**
In conclusion, this project is focused on predicting customer churn in the telecom industry. By following the outlined steps and utilizing the selected models, we aim to provide valuable insights and recommendations for reducing churn and improving customer retention.
