# Bank-Churn-Prediction-using-Random-Forest


## Introduction

Customer churn prediction involves identifying customers who are likely to leave or unsubscribe from a service. For many companies, this prediction is critical, as acquiring new customers often costs more than retaining existing ones. Understanding the behaviors and preferences of customers allows businesses to tailor their marketing efforts effectively, maximizing customer retention.
![23000](https://github.com/user-attachments/assets/0ea1f329-bfab-4c54-8980-789fc3dc1ce8)


## Impact of Customer Churn on Businesses

High churn rates can significantly affect a company's growth, sales, and earnings. Conversely, businesses with low churn rates can maintain their customer base and experience steady growth. Analyzing customer churn is crucial for a firm's success, as effective customer retention strategies can enhance the average customer lifetime value, leading to increased sales and profitability.

## Problem Statement

Customer churn or attrition refers to the tendency of customers to discontinue using a company’s products or services. A notable churn rate can result from unsatisfactory experiences, leading to significant financial losses and reputational damage. In this project, we aim to predict the churn rate for “ABC BANK” by employing various machine learning approaches.

## Dataset Description

The dataset used for this project is a public dataset containing **10,000 rows** and **14 columns**. The target variable is `Exited`, indicating whether a customer has left the bank.

### Data Dictionary

| Variable            | Definition                                           |
|---------------------|------------------------------------------------------|
| RowNumber           | Unique Row Number                                    |
| CustomerId          | Unique Customer Id                                   |
| Surname             | Surname of a customer                                |
| CreditScore         | Credit Score of each Customer                        |
| Geography           | Geographical Location of Customers                   |
| City_Category       | Category of the City (A, B, C)                       |
| Gender              | Sex of Customers                                     |
| Age                 | Age of Each Customer                                 |
| Tenure              | Number of years                                      |
| Balance             | Current Balance of Customers                          |
| NumOfProducts       | Number of Products                                   |
| HasCrCard           | If a customer has a credit card or not               |
| IsActiveMember      | If a customer is active or not                       |
| EstimatedSalary     | Estimated Salary of each Customer                    |
| Exited              | Customer left the bank or Not (Target Variable)      |



### Accuracy

The Random Forest Classifier model achieved the highest accuracy of **89.53%**.

| Models                                       | Training Accuracy Score | Testing Accuracy Score |
|----------------------------------------------|-------------------------|------------------------|
| Logistic Regression                          | 88.00%                  | 81.41%                 |
| Random Forest                                | 94.42%                  | 89.53%                 |
| Support Vector Machine (SVM) (RBF kernel)   | 90.00%                  | 86.00%                 |
| Support Vector Machine (SVM) (Poly kernel)   | 91.53%                  | 85.32%                 |
| Stochastic Gradient Descent (SGD)          | 90.47%                  | 81.78%                 |
| XGBoost Classifier                          | 96.45%                  | 88.81%                 |
| Neural Network classifier                    | 89.67%                  | 84.35%                 |
| Neural Network classifier with Early Stopping | 89.67%                  | 84.35%                 |
| Neural Network Architecture with multiple Hidden layers | 86.67%            | 86.20%                 |
| Neural Network Architecture with Early Stopping | 86.65%                  | 86.23%                 |

## Conclusion

Predicting customer churn is essential for developing effective retention strategies. Low false positive rates are crucial, as high rates can lead to unnecessary promotional efforts directed at customers who are not actually churning. Therefore, precision is a key evaluation metric in this context.

