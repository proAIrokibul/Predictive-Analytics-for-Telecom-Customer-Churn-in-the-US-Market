# Customer Churn Prediction and Analysis

## Overview
This repository provides a comprehensive solution for predicting customer churn using machine learning techniques. The project encompasses data preprocessing, exploratory data analysis (EDA), advanced visualizations, and implementation of multiple classification algorithms. The results of these models are compared to identify the most effective solution for predicting churn.

## Key Features
### 1. Data Preprocessing
- **Missing Value Handling**: Filled missing values in the `InternetService` column with the mode.
- **Categorical Encoding**: Encoded categorical variables like `Gender`, `ContractType`, and `InternetService` using Label Encoding.
- **Feature Scaling**: Applied Standard Scaling to numerical columns (`Age`, `Tenure`, `MonthlyCharges`, `TotalCharges`) for uniformity.

### 2. Exploratory Data Analysis (EDA)
- **Churn Distribution**: Analyzed the distribution of churned vs. non-churned customers.
- **Key Insights**:
  - Monthly charges and tenure trends in relation to churn.
  - Contract type preferences among customers.
- **Correlation Analysis**: Heatmap visualization to reveal feature relationships.

### 3. Visualizations
- **Churn Distribution**: Count plots of churned and non-churned customers.
- **Monthly Charges Distribution**: Histogram with density estimation.
- **Tenure Trends**: KDE plot to analyze tenure variations by churn status.
- **Box Plots**: Gender vs. monthly charges for churn analysis.
- **Correlation Heatmap**: Comprehensive view of feature interdependencies.

### 4. Machine Learning Models
- **Random Forest**: Achieved the best performance with 100% accuracy on the test data.
- **Support Vector Machine (SVM)**: High performance with an accuracy of 92%.
- **Logistic Regression**: Comparable performance to SVM with 92% accuracy.

### 5. Model Comparison
- Detailed comparison of model accuracy using bar charts.
- Visualization of confusion matrices for each model.

## Results
### Random Forest
- **Accuracy**: 1.00
- **Classification Report**:
  - Precision, Recall, F1-Score: 1.00 across all metrics.

### Support Vector Machine
- **Accuracy**: 0.92
- **Classification Report**:
  - Precision: 0.73 (Class 0), 0.94 (Class 1)
  - Recall: 0.48 (Class 0), 0.98 (Class 1)

### Logistic Regression
- **Accuracy**: 0.92
- **Classification Report**:
  - Precision: 0.73 (Class 0), 0.94 (Class 1)
  - Recall: 0.48 (Class 0), 0.98 (Class 1)

## Business Impact
Customer churn has a direct impact on revenue and growth for businesses in telecom, financial services, and other subscription-based models. This project offers:
- **Revenue Retention**: Identifying at-risk customers allows businesses to focus on retention strategies.
- **Improved Customer Insights**: Insights into churn drivers enable tailored offerings and better customer experiences.
- **Strategic Decision Making**: Enhances planning for pricing, services, and support initiatives.


