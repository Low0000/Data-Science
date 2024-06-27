# Analyzing Customer Churn in Banking

## Project Overview
This data science project aims to understand and predict customer churn in a bank by analyzing demographic, behavioral, and financial data. The goal is to identify key factors contributing to churn and build predictive models to forecast future churn, enabling the bank to implement targeted retention strategies.

## Steps and Findings

### Step 1: Data Collection
- Loaded and examined the dataset for missing values and data types.
- Ensured the data was clean with no missing values.

### Step 2: Data Preprocessing
- Dropped irrelevant columns for the analysis.
- Summarized data to understand churn distribution.

### Step 3: Exploratory Data Analysis (EDA)
**Descriptive Analysis:**
- Compared demographic characteristics (age, gender, dependent count, education level) of churned vs. non-churned customers.
- Visualized distributions and counts for insights into churn patterns.

**Exploratory Analysis:**
- Examined correlations to identify the strongest numerical feature related to Avg_Open_To_Buy, finding Credit_Limit as the strongest predictor.

**Inferential Analysis:**
- Tested the hypothesis that higher credit card usage is linked to lower churn rates.
- Confirmed that both transaction count and amount are significantly higher for non-churned customers.

### Step 4: Data Mining and Predictive Modeling
- Used Random Forest Classifier to predict customer churn.
- Achieved a high prediction accuracy of 95%.
- Identified top predictors of churn, including Total_Trans_Amt, Total_Trans_Ct, and Credit_Limit.

### Key Insights
- Customers with higher transaction counts and amounts are less likely to churn.
- Financial metrics are strong indicators of customer churn risk.
- Transactional behavior is a critical factor in predicting churn.

## Conclusion
By focusing on key behavioral and financial metrics, the bank can better understand and mitigate churn risk. The insights from this analysis can guide effective customer retention strategies, enhancing overall business performance.

## Visualizations
- Correlation heatmaps
- Distribution plots of demographic and transaction characteristics
- Confusion matrix for model evaluation
- Feature importance bar plots
