# Customer Churn Analysis (EDA)

## Project Overview

Customer churn is one of the most important business metrics for subscription-based companies. Understanding why customers leave helps organizations improve retention strategies and reduce revenue loss.
This project performs an in-depth Exploratory Data Analysis (EDA) on the Telco Customer Churn dataset to identify key factors contributing to customer attrition and uncover actionable business insights.

---

## Objectives

- Clean and preprocess customer churn data.
- Analyze customer demographics and service usage patterns.
- Identify factors associated with customer churn.
- Visualize churn behavior across different customer segments.
- Generate business insights that can help improve customer retention.

---

## Dataset

**Dataset:** Telco Customer Churn Dataset

The dataset contains customer information such as:

- Customer demographics
- Account information
- Service subscriptions
- Contract details
- Payment methods
- Customer tenure
- Churn status

### Key Features

| Feature | Description |
|----------|-------------|
| gender | Customer gender |
| SeniorCitizen | Whether customer is a senior citizen |
| Partner | Whether customer has a partner |
| Dependents | Whether customer has dependents |
| tenure | Number of months with the company |
| Contract | Contract type |
| InternetService | Internet service type |
| PaymentMethod | Customer payment method |
| MonthlyCharges | Monthly billing amount |
| TotalCharges | Total amount charged |
| Churn | Customer churn status |

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Data Cleaning

The following preprocessing steps were performed:


- Checked dataset structure and data types
- Handled missing values
- Converted `TotalCharges` to numeric format
- Verified duplicate records
- Converted encoded categorical values into readable labels
- Performed basic statistical analysis

---

## Exploratory Data Analysis

The analysis includes:

### 1. Churn Distribution
- Overall churn rate analysis
- Customer retention vs churn comparison

### 2. Demographic Analysis
- Gender-wise churn comparison
- Senior citizen churn analysis
- Partner and dependent impact on churn

### 3. Customer Tenure Analysis
- Relationship between customer tenure and churn
- Identification of high-risk customer groups

### 4. Contract Analysis
- Month-to-month contracts
- One-year contracts
- Two-year contracts

### 5. Service-Based Analysis
- Internet service type impact
- Online security subscriptions
- Online backup services
- Device protection plans
- Tech support subscriptions
- Streaming services

### 6. Payment Method Analysis
- Churn behavior across payment methods
- Electronic check customer analysis

---

## Key Insights

### Customer Churn Rate
- Approximately **26.5%** of customers have churned.

### Senior Citizens
- Senior citizens show a higher churn percentage compared to non-senior customers.

### Customer Tenure
- Customers with shorter tenure are more likely to churn.
- Long-term customers tend to remain loyal.

### Contract Type
- Month-to-month customers have the highest churn rates.
- Customers with long-term contracts are significantly less likely to leave.

### Internet Services
- Customers using Fiber Optic services exhibit higher churn rates compared to DSL users.

### Value-Added Services
Customers subscribed to:
- Online Security
- Online Backup
- Device Protection
- Tech Support

show lower churn rates, indicating these services improve customer retention.

### Payment Methods
- Customers using **Electronic Check** have the highest churn tendency.

---

## Business Recommendations

Based on the analysis:

1. Encourage customers to switch from month-to-month contracts to long-term plans.
2. Improve onboarding experiences for new customers.
3. Promote security and support-related services.
4. Investigate causes of churn among Fiber Optic users.
5. Create retention campaigns targeting Electronic Check users.
6. Develop loyalty programs for high-risk customer segments.


---

## Future Improvements

- Build machine learning models for churn prediction.
- Perform feature engineering.
- Create an interactive dashboard using Power BI or Tableau.
- Deploy churn prediction as a web application.

---

## Conclusion

This EDA reveals several important drivers of customer churn, including contract type, tenure, internet service, payment methods, and additional service subscriptions. The insights generated can help businesses implement targeted retention strategies and improve customer satisfaction.

---

## Author

Jamshed Ali

If you found this project useful, consider giving it a ⭐ on GitHub.
