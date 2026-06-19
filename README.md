# telecom-Customer-churn-analysis

## Project Overview

Customer churn is one of the most important metrics for subscription-based businesses. This project analyzes customer demographics, services, contracts, payment methods, and account information to identify the factors contributing to customer churn.

The objective is to uncover key churn drivers, understand customer behavior, and provide actionable business recommendations to improve customer retention.

---

## Dataset Information

The dataset contains customer information, including:

* Customer Demographics

  * Gender
  * Senior Citizen Status
  * Partner
  * Dependents

* Account Information

  * Tenure
  * Contract Type
  * Paperless Billing
  * Payment Method
  * Monthly Charges
  * Total Charges

* Services Subscribed

  * Phone Service
  * Multiple Lines
  * Internet Service
  * Online Security
  * Online Backup
  * Device Protection
  * Tech Support
  * Streaming TV
  * Streaming Movies

* Target Variable

  * Churn (Yes/No)

---

## Project Objectives

* Analyze customer churn patterns.
* Identify factors associated with higher churn rates.
* Compare churn behavior across customer segments.
* Generate business insights for customer retention.
* Visualize key trends using charts and graphs.

---

## Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook / Google Colab

---

## Data Cleaning and Preprocessing

The following preprocessing steps were performed:

* Removed unnecessary columns.
* Checked for missing values.
* Converted data types where required.
* Handled categorical variables.
* Verified data consistency.
* Prepared data for visualization and analysis.

---

## Exploratory Data Analysis (EDA)

The analysis focused on:

### Customer Demographics

* Churn by Gender
* Churn by Senior Citizen Status
* Churn by Partner Status
* Churn by Dependents

### Customer Account Information

* Churn by Tenure
* Churn by Contract Type
* Churn by Payment Method
* Churn by Monthly Charges
* Churn by Total Charges

### Service Analysis

* Churn by Internet Service
* Churn by Online Security
* Churn by Online Backup
* Churn by Device Protection
* Churn by Tech Support
* Churn by Streaming Services

---

## Key Findings

### Overall Churn Rate

* Approximately **26.5%** of customers have churned.
* Around **73.5%** of customers remain with the company.

### Customer Tenure

* Customers with shorter tenure are more likely to churn.
* Long-term customers demonstrate stronger loyalty.

### Contract Type

* Month-to-month contracts show the highest churn rates.
* One-year and two-year contracts have significantly lower churn.

### Internet Service

* Fiber Optic customers exhibit higher churn rates compared to DSL customers.

### Value-Added Services

Customers without:

* Online Security
* Online Backup
* Device Protection
* Tech Support

show considerably higher churn rates.

### Payment Method

* Electronic Check users have the highest churn count.
* Customers using automatic payment methods are more likely to stay.

---

## Business Recommendations

1. Encourage customers to switch to long-term contracts.
2. Improve retention strategies for Fiber Optic customers.
3. Promote Online Security and Tech Support services.
4. Incentivize automatic payment methods.
5. Focus on customer engagement during the early stages of the customer lifecycle.

---

## Project Structure

```text
Customer-Churn-Analysis/
│
├── Customer_Churn.csv
├── Churn_analysis.ipynb
├── README.md
└── Visualizations/
```

---

## Conclusion

This analysis highlights that customer churn is primarily influenced by contract type, tenure, internet service type, payment method, and subscription to support-related services. By targeting high-risk customer segments and implementing retention-focused strategies, businesses can reduce churn and improve long-term customer value.

---

## Author

Tanmay

Data Analytics Project using Python, Pandas, Matplotlib, and Seaborn.

