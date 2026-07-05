# 📊 Customer Churn & Retention Dashboard (Power BI)

A comprehensive **Customer Churn & Retention Dashboard** built using **Microsoft Power BI** to analyze customer behavior, identify churn patterns, measure customer lifetime value (CLV), and evaluate retention performance. The dashboard provides actionable insights that help businesses reduce customer attrition and improve customer loyalty through interactive visualizations and KPIs.

---

# 📌 Project Overview

Customer retention is one of the most important factors for business growth. This dashboard helps organizations monitor customer churn, identify the factors contributing to customer loss, and understand customer retention trends.

The dashboard combines customer demographic, contract, payment, tenure, and billing information into a single interactive report, enabling business users to make informed decisions for improving customer satisfaction and long-term profitability.

---

# 🎯 Objectives

- Monitor customer churn and retention rates.
- Analyze customer lifetime value (CLV).
- Identify customer segments with high churn.
- Understand the impact of contract types on churn.
- Evaluate churn across different payment methods.
- Analyze customer tenure and monthly charges.
- Support customer retention strategies using data-driven insights.

---

# ✨ Dashboard Features

- 👥 Total Customers KPI
- 💰 Average Customer Lifetime Value (CLV)
- 📉 Customer Churn Rate
- 📈 Customer Retention Rate
- 📄 Churn Analysis by Contract Type
- ⏳ Churn Analysis by Customer Tenure
- 💳 Churn Analysis by Payment Method
- 💵 Monthly Charges Distribution
- 📋 Customer Summary Table
- 📊 Customer Relationship Scatter Plot
- Interactive Filters and Cross-Filtering
- Clean and User-Friendly Dashboard Design

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Microsoft Power BI | Dashboard Development |
| Power Query | Data Cleaning & Transformation |
| DAX (Data Analysis Expressions) | KPI and Measure Calculations |
| Excel / CSV Dataset | Data Source |
| Data Modeling | Relationship Management |
| Power BI Visualizations | Business Intelligence |

---

# 📊 Dashboard Overview

The dashboard provides an executive overview of customer retention and churn metrics through interactive visualizations.

---

## KPI Cards

The dashboard displays four key performance indicators:

- 👥 **Total Customers:** 7,032
- 💰 **Average Customer Lifetime Value (CLV):** 2.10K
- 📉 **Customer Churn Rate:** 26.58%
- 📈 **Customer Retention Rate:** 73.42%

These KPIs provide a quick summary of overall customer health and business performance.

---

## Churn Rate by Contract Type

A horizontal bar chart compares churn across different contract types.

### Insights

- Month-to-Month contracts have the highest churn rate.
- One-Year contracts show significantly lower churn.
- Two-Year contracts retain customers the best.
- Long-term contracts improve customer loyalty.

---

## Churn Rate by Customer Tenure

A bar chart visualizes churn across customer tenure groups.

### Insights

- New customers (0–12 months) experience the highest churn.
- Churn decreases as customer tenure increases.
- Long-term customers are more likely to remain loyal.
- Customer onboarding plays an important role in retention.

---

## Churn Rate by Payment Method

This visualization compares churn rates for different payment methods.

### Insights

- Electronic Check customers have the highest churn.
- Automatic payment methods show lower churn.
- Customers using bank transfers and credit cards are generally more stable.
- Payment preferences influence customer retention.

---

## Churn Rate by Monthly Charges

A histogram illustrates churn based on monthly billing amounts.

### Insights

- Higher monthly charges are associated with increased churn.
- Customers paying moderate charges have better retention.
- Pricing strategies may impact customer loyalty.

---

## Customer Summary Table

The dashboard includes a detailed table showing:

- Customer Tenure Groups
- Active Customers
- Churned Customers
- Total Customers

### Insights

- Provides detailed customer distribution.
- Helps compare retention across tenure segments.
- Useful for identifying high-risk customer groups.

---

## Customer Relationship Analysis

A scatter plot compares:

- Customer Tenure
- Total Charges
- Monthly Charges

### Insights

- Customers with longer tenure generally generate higher total revenue.
- Higher total charges often indicate long-term customer relationships.
- Helps identify valuable customer segments.

---

# 📂 Dashboard Components

The dashboard includes:

- KPI Cards
- Horizontal Bar Charts
- Column Charts
- Histogram
- Scatter Plot
- Customer Summary Table
- Interactive Filters

---

# 📈 Key Business Insights

- The overall customer churn rate is **26.58%**.
- More than **73%** of customers are retained.
- Month-to-Month contracts have the highest churn.
- Customers with longer tenure are significantly more loyal.
- Electronic Check payment method is associated with higher churn.
- Higher monthly charges increase the likelihood of churn.
- Long-term customers contribute greater customer lifetime value.
- Customer retention improves business profitability.

---

# 🔄 Data Processing Workflow

```
Raw Customer Dataset
        │
        ▼
 Data Cleaning
(Power Query)
        │
        ▼
 Data Transformation
        │
        ▼
 Data Modeling
(Relationships)
        │
        ▼
 DAX Measures
(KPIs)
        │
        ▼
 Interactive Visualizations
        │
        ▼
 Customer Churn Dashboard
```

---

# 📐 DAX Measures Used

Example DAX calculations:

```DAX
Total Customers = COUNT(Customer[CustomerID])

Churn Rate =
DIVIDE(
    CALCULATE(COUNT(Customer[CustomerID]), Customer[Churn]="Yes"),
    [Total Customers]
)

Retention Rate = 1 - [Churn Rate]

Average CLV =
AVERAGE(Customer[TotalCharges])
```

---

# 📷 Dashboard Preview

The dashboard includes:

- KPI Cards
- Customer Churn Rate
- Retention Rate
- Churn by Contract Type
- Churn by Tenure Group
- Churn by Payment Method
- Monthly Charges Distribution
- Customer Summary Table
- Customer Relationship Analysis

(Add dashboard screenshots here.)

---

# 💼 Skills Demonstrated

- Business Intelligence
- Customer Analytics
- Power BI Dashboard Development
- Data Cleaning
- Power Query
- DAX Calculations
- Data Modeling
- KPI Development
- Data Visualization
- Business Analytics
- Customer Segmentation
- Data Storytelling

---

# 🚀 Future Improvements

- Customer Churn Prediction using Machine Learning
- Customer Segmentation Dashboard
- Customer Satisfaction Analysis
- Geographic Customer Analysis
- Real-Time Dashboard Updates
- Drill-Through Customer Profiles
- Subscription Renewal Forecasting
- Customer Risk Scoring
- Automated Data Refresh
- Mobile Dashboard Optimization

---

# ▶️ How to Open the Project

1. Clone this repository.

```bash
git clone https://github.com/yourusername/Customer-Churn-Dashboard.git
```

2. Open the `.pbix` file using **Microsoft Power BI Desktop**.

3. Refresh the dataset if required.

4. Explore the interactive dashboard.

---

# Screenshots
<img width="944" height="537" alt="image" src="https://github.com/user-attachments/assets/2d111436-6c5e-4eb0-84c4-5614df523e47" />

<img width="943" height="467" alt="image" src="https://github.com/user-attachments/assets/ebcde313-71e2-4442-a7fe-017149aaef8f" />

---

# 🎓 Learning Outcomes

This project helped me gain practical experience in:

- Building professional Power BI dashboards.
- Designing customer analytics reports.
- Creating KPIs using DAX.
- Cleaning and transforming customer data.
- Identifying churn patterns using visual analytics.
- Developing business insights to improve customer retention.
- Presenting customer behavior through interactive visualizations.

---

# 👨‍💻 Author

**Yash Nimat**

If you found this project useful, consider giving it a ⭐ on GitHub.
