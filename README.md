# Telco-Customer-Churn-Prediction-and-Analysis

## Overview
Customer churn poses a significant challenge to businesses, impacting profitability and sustainability. This project uses the **Telco Customer Churn dataset** from Kaggle to build predictive models and provide insights for minimizing churn rates.

## Key Features
- **Exploratory Data Analysis (EDA):** Insights into customer demographics, behaviors, and services.
- **Machine Learning Models:** Implementation of Logistic Regression, Random Forest, and XGBoost models.
- **Preprocessing Techniques:** Feature scaling, encoding, resampling (SMOTE), and feature selection.
- **Model Evaluation:** Focus on metrics like recall, F1-score, and expected value to ensure business applicability.
- **Actionable Recommendations:** Strategies to improve customer retention and enhance profitability.

## Dataset
The dataset includes:
- Customer demographics (e.g., gender, senior citizen, partner, dependents).
- Account information (e.g., tenure, contract type, payment method, monthly charges).
- Service details (e.g., internet service, tech support, streaming services).
- Churn status as the target variable.

## Key Findings
- Customers with **shorter tenures** are more likely to churn.
- **Monthly charges** and **contract type** significantly impact churn rates.
- Customers using **electronic checks** are more likely to churn compared to other payment methods.

## Models and Performance
- **Logistic Regression:** High accuracy and baseline model for comparison.
- **Random Forest:** Best model overall with balanced precision and recall.
- **XGBoost:** Strong recall and expected value, closely matching Random Forest.

## Recommendations
1. **Retention Strategies:**
   - Focus on at-risk customers with shorter tenures or higher monthly charges.
   - Offer personalized plans and loyalty incentives.

2. **Business Implementation:**
   - Develop dashboards for real-time churn monitoring.
   - Use predictive insights to target high-risk customers.

3. **Model Enhancements:**
   - Experiment with hyperparameter tuning and advanced feature engineering.
   - Explore additional resampling techniques to handle class imbalance.
