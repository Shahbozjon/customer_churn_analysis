# **Customer Churn Analysis: EDA & Classification Models**
## Project Overview
In todays commercial world competition is high and every customer is valuable. Understanding the customer is of utmost importance, including being able to understand the behavior patterns of that customer. Customer Churn is the rate at which a commercial customer leaves the commercial business and takes their money elsewhere. Understanding customer churn is vital to the success of a company and a churn analysis is the first step to understanding the customer.

This notebook presents a customer churn classification project using Logistic Regression, Support Vector Machines, Decision Tree, Random Forest, XGBoost and CatBoost models. The goal is to clasify whether customers will churn (leave) a subscription-based service.

## The Data
The data is sourced from Kaggle (https://www.kaggle.com/code/wonderdavid/e-commerce-customer-churn-prediction/input?select=E+Commerce+Dataset.xlsx). Our dataset contains 5630 entries representing 5630 unique customers. There are 20 columns (target feature = 'Churn'). The features are numeric and categorical in nature, so we will need to address these differences before modeling.
