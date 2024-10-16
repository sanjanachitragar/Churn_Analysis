# 📊 Customer Churn Analysis 
## 📖 Overview
Customer churn analysis is an essential aspect of customer relationship management. This project aims to build a robust pipeline that addresses data extraction, model development, and system design using the Telco Customer Churn dataset from Kaggle.

## 🔍 Problem Statement
The main goal of this analysis is to understand the factors influencing customer churn in the telecom sector. By identifying these factors, companies can take proactive measures to retain customers and improve service quality.

## 📁 Dataset
The dataset used in this project is the [Telco Customer Churn dataset](https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset?select=Telco_customer_churn.xlsx) from Kaggle.

## 🔧 Data Preparation
1. **Data Loading**: The dataset is loaded using Pandas.
2. **Feature Engineering**: 
   - Added a time feature with daily frequency.
   - Converted the `Total Charges` column from `object` to `float`.
3. **Missing Values Handling**: 
   - Imputed missing values in the `Total Charges` column based on calculated values from `Monthly Charges`.
   - Imputed missing values in the `Churn Reason` column with "Not Applicable".

## 📊 Exploratory Data Analysis (EDA)
- Conducted thorough EDA to understand data quality and feature distributions.
- Created visualizations for:
  - Churn rates by gender and age groups.
  - Distribution of tenure months among churned and non-churned customers.
  - Churn reasons and their frequencies.

## 🔄 Feature Engineering
- Cleaned the dataset by removing unnecessary columns.
- Encoded categorical variables to numerical format for modeling.

## 📈 Model Development
1. **Correlation and Covariance Analysis**: 
   - Visualized the correlation between features to identify significant relationships.
2. **Churn Prediction Models**: (To be implemented)
   - Plan to develop predictive models to evaluate customer churn.

## 📊 Results
- Key findings include:
  - The highest churn rate among customers with electronic check payment methods.
  - The significant impact of internet service type on customer retention.
  - Senior citizens exhibit a higher churn rate compared to non-senior citizens.

## 🚀 Next Steps
- Implement predictive modeling techniques.
- Optimize the model based on evaluation metrics.
- Create a user-friendly dashboard to visualize churn predictions.

🔗 **Links:**
- [Kaggle Dataset](https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset?select=Telco_customer_churn.xlsx)
- [GitHub Repository](https://github.com/sanjanachitragar/Churn_Analysis)
