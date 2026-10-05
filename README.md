# 🛍️ Retail Customer Behaviour & Business Analytics

End-to-end retail customer analytics using Python, SQL, Excel and Power BI to uncover customer behaviour, sales trends and business insights.

---

## Overview

Retail Customer Behaviour & Business Analytics is a data analytics project focused on understanding customer purchasing patterns, product performance and revenue trends using an end-to-end analytics workflow.

The project covers data loading, exploratory data analysis, data cleaning, SQL-based business analysis and interactive Power BI dashboard development.

The analysis focuses on identifying customer segments, subscription behaviour, product/category performance, demographic trends and purchasing patterns to support data-driven business decisions.

---

## Objective

The objective of this project is to analyze retail customer and transaction data to identify meaningful business patterns and generate actionable insights.

The project focuses on:

- Understanding customer purchasing behaviour.
- Analyzing revenue and sales across product categories.
- Examining customer demographics and age-group trends.
- Evaluating subscription and shipping behaviour.
- Identifying patterns in repeat purchases and customer engagement.
- Building an interactive dashboard for business reporting and decision-making.

---

## Dataset

The dataset contains customer transaction and behavioural information used to analyze purchasing patterns and business performance.

Key attributes include:

- Customer ID
- Age / Age Group
- Gender
- Product Category
- Purchase Amount
- Subscription Status
- Shipping Type
- Review Rating
- Purchase Behaviour
- Customer Demographics

The analysis was performed on 3,900+ customer transaction records.

---

## Tools & Technologies

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=databricks&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

---

## Workflow

### 1. Data Loading and Inspection

- Loaded the customer transaction dataset using Python and Pandas.
- Examined dataset structure, data types and statistical properties.
- Identified numerical and categorical variables.
- Reviewed customer demographics, purchasing and product-related attributes.

### 2. Data Cleaning

The dataset was prepared for analysis by:

- Identifying and handling missing values.
- Checking data consistency and duplicate records.
- Standardizing categorical and numerical attributes.
- Preparing analytical fields for customer and sales analysis.

### 3. Exploratory Data Analysis

Performed exploratory analysis to identify:

- Customer purchasing patterns.
- Revenue distribution across product categories.
- Sales contribution by age groups.
- Subscription behaviour.
- Product and customer trends.

### 4. SQL Business Analysis

Executed SQL-based analytical queries to derive business insights related to:

- Customer demographics.
- Product category performance.
- Revenue and sales trends.
- Repeat-purchase behaviour.
- Online vs. offline sales channels.

### 5. Power BI Dashboard

Developed an interactive Power BI dashboard featuring:

- Total Customers
- Average Purchase Amount
- Average Review Rating
- Subscription Status
- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Sales by Age Group
- Interactive filters for Gender, Category and Shipping Type

---

## Dashboard

The Power BI dashboard provides an interactive view of customer behaviour and business performance through KPIs, charts, and filters.

Key dashboard areas include:

- Customer behaviour
- Purchase trends
- Product categories
- Demographic analysis
- Seasonal analysis
- Online vs. offline channels
- Payment preferences
- Customer engagement indicators

### Key Dashboard Metrics

- **3.9K** Customers
- **$59.76** Average Purchase Amount
- **3.75** Average Review Rating
- **27%** Subscribed Customers

The dashboard enables users to filter and analyze customer behaviour based on demographic and transactional attributes.

---

## Key Insights

The analysis identifies actionable patterns in customer purchasing behaviour and provides insights that can support:

- Customer segmentation
- Targeted marketing campaigns
- Promotional and discount strategies
- Product planning
- Customer engagement
- Sales-channel optimization
- Repeat-purchase strategies

> Quantitative findings and detailed business recommendations are available in the project report and Power BI dashboard.

---

## Project Structure

```text
Retail_Customer_Behaviour_Analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── customer_trend_analysis.ipynb
│
├── powerbi/
│   └── customer_behaviour_dashboard.pbix
|
└── README.md
```

## How to Run

### Python Analysis

1. Clone the repository.
2. Open the Python/Jupyter Notebook files.
3. Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn
