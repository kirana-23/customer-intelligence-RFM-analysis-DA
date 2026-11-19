# Customer Intelligence & RFM Analysis

<p align="center">
  <img src="https://img.shields.io/badge/Python-Data%20Analysis-blue?logo=python" />
  <img src="https://img.shields.io/badge/SQL-Data%20Analysis-orange?logo=mysql" />
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter" />
</p>

## 1. Project Overview

Understanding customer purchasing behaviour is essential for businesses to improve customer retention, optimize marketing strategies, and maximize revenue.

This project focuses on Customer Intelligence and RFM (Recency, Frequency, Monetary) Analysis to evaluate customer purchasing patterns and identify meaningful customer segments.

Using Python, SQL, and Power BI, the project analyzes transactional data, calculates customer-level RFM metrics, and categorizes customers based on their purchasing behaviour and monetary contribution.

The objective is to transform transactional data into actionable customer insights that help businesses recognize valuable customers, identify customers requiring retention efforts, and develop more targeted marketing strategies.

## 2. Business Problem

Businesses often treat all customers similarly, despite differences in purchasing frequency, spending patterns, and engagement.

Without customer segmentation, it becomes difficult to:

- Identify high-value customers who contribute significantly to revenue.
- Recognize loyal customers and frequent purchasers.
- Detect customers whose purchasing activity has declined.
- Prioritize customer retention initiatives.
- Develop targeted marketing and promotional campaigns.
- Allocate marketing resources effectively.

This project addresses these challenges through data-driven RFM segmentation and customer behaviour analysis.

## 3. Business Objectives

- Analyze customer purchasing behaviour and transaction patterns.
- Calculate Recency, Frequency, and Monetary metrics.
- Develop RFM-based customer scores and segments.
- Identify high-value and loyal customer groups.
- Recognize at-risk and inactive customer segments.
- Analyze customer contribution to overall revenue.
- Generate actionable recommendations for customer retention and targeted marketing.
- Present customer intelligence insights through an interactive Power BI dashboard.

## 4. RFM Analysis Framework

RFM analysis evaluates customers using three key behavioural metrics.

| Metric | Definition | Business Significance |
|---|---|---|
| Recency | Time elapsed since the customer's last purchase | Measures customer activity and engagement |
| Frequency | Number of purchases made by a customer | Measures purchasing frequency and loyalty |
| Monetary | Total amount spent by a customer | Measures customer value and revenue contribution |

### RFM Scoring

Customers are evaluated using Recency, Frequency, and Monetary scores to distinguish different purchasing behaviour patterns.

The resulting RFM scores support customer segmentation and help identify groups with different retention and marketing priorities.

## 5. Technology Stack

| Technology | Application |
|---|---|
| Python | Data cleaning, manipulation, and exploratory analysis |
| Pandas | Data processing and aggregation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| SQL | Customer-level analysis and business queries |
| Power BI | Interactive customer analytics dashboard |
| Jupyter Notebook | Analysis and documentation |

## 6. Project Workflow

### 6.1 Data Understanding
- Examined the structure and dimensions of the customer and transaction datasets.
- Reviewed customer attributes and transaction-level information.
- Identified relevant fields required for customer analysis.
- Examined data types and data quality.

### 6.2 Data Cleaning and Preparation
- Checked for missing values and duplicate records.
- Reviewed data consistency and validity.
- Prepared transaction dates and numerical fields for analysis.
- Combined relevant customer and transaction information where required.
- Prepared structured data for customer-level aggregation.

### 6.3 Exploratory Data Analysis (EDA)
Performed exploratory analysis to understand customer purchasing behaviour and business performance.

Analysis areas included:
- Customer purchasing patterns.
- Transaction and revenue distribution.
- Customer spending behaviour.
- Purchase frequency.
- Customer-level revenue contribution.
- Distribution of customer activity.

### 6.4 RFM Feature Engineering
Calculated customer-level RFM metrics:

- **Recency:** Time since the most recent purchase.
- **Frequency:** Total number of purchases.
- **Monetary:** Total purchase value.

These metrics provide a structured representation of customer purchasing behaviour.

### 6.5 Customer Segmentation
Applied RFM scoring to categorize customers according to their purchasing activity and value.

The segmentation supports the identification of:
- High-value customers.
- Loyal and frequent customers.
- Potential customers with growth opportunities.
- Customers requiring retention efforts.
- Inactive or lost customers.

*The final segment names and scoring rules should match the implementation in the notebook.*

### 6.6 SQL-Based Analysis
Used SQL to explore customer and transaction data through business-focused queries.

Analysis areas included:
- Customer purchasing frequency.
- Customer spending patterns.
- Revenue contribution.
- Customer-level aggregations.
- RFM-related business analysis.

### 6.7 Power BI Dashboard Development
Developed an interactive dashboard to communicate customer intelligence insights.

The dashboard supports:
- Customer segmentation analysis.
- RFM metric exploration.
- Customer value comparison.
- Purchasing behaviour analysis.
- Revenue contribution analysis.
- Business-oriented customer insights.

## 7. Key Business Analysis Areas

| Analysis Area | Business Purpose |
|---|---|
| Recency Analysis | Identify recently active and inactive customers |
| Frequency Analysis | Understand customer purchase frequency |
| Monetary Analysis | Evaluate customer spending and value |
| RFM Segmentation | Group customers based on purchasing behaviour |
| Customer Value Analysis | Identify valuable customer groups |
| Revenue Contribution | Understand how customers contribute to revenue |
| Retention Analysis | Identify customers who may require engagement |
| Purchasing Behaviour | Understand customer transaction patterns |

## 8. Business Recommendations

- **Customer Retention:** Develop targeted retention campaigns for customers showing declining purchasing activity.
- **Loyalty Programs:** Reward frequent and high-value customers through personalized benefits.
- **Targeted Marketing:** Design segment-specific promotional campaigns instead of applying the same strategy to all customers.
- **Customer Reactivation:** Introduce win-back campaigns for inactive customers.
- **Revenue Optimization:** Prioritize customer groups with strong monetary contributions.
- **Customer Engagement:** Monitor purchasing activity and RFM metrics regularly to identify changes in customer behaviour.

## 9. Dashboard Preview

The Power BI dashboard presents customer segmentation and purchasing behaviour through interactive visualizations.

![Customer Intelligence RFM Dashboard](dashboard.png)

## 10. Repository Structure

```text
customer-intelligence-RFM-analysis-DA/
│
├── Customer_Intelligence_RFM_Analysis.ipynb
├── customer_data.csv
├── customer_transactions.csv
├── customer_analysis.sql
├── customer_rfm_dashboard.pbix
├── dashboard.png
├── README.md
├── requirements.txt
└── .gitignore
```

*Replace the example filenames above with the exact filenames present in your repository.*

## 11. How to Run the Project

### Clone the Repository

```bash
git clone https://github.com/kirana-23/customer-intelligence-RFM-analysis-DA.git
```

### Navigate to the Project Directory

```bash
cd customer-intelligence-RFM-analysis-DA
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Python Notebook

```bash
jupyter notebook
```

Open the RFM analysis notebook and execute the cells.

Ensure the required datasets are available in the paths specified in the notebook.

### Run SQL Analysis

Open the SQL script using MySQL Workbench or another compatible SQL environment and execute the customer analysis queries against the prepared dataset.

### Explore the Power BI Dashboard

Open the Power BI file using Power BI Desktop to explore customer segmentation and purchasing behaviour.

## 12. Project Deliverables

| Deliverable | Description |
|---|---|
| Python Notebook | Data preparation, EDA, and RFM analysis |
| SQL Script | Customer-level business analysis |
| Prepared Dataset | Structured data used for analysis |
| Power BI Dashboard | Interactive customer intelligence reporting |
| README | Project documentation |

## 13. Future Enhancements

- Integrate customer lifetime value (CLV) analysis.
- Explore customer purchase trends over time.
- Develop customer churn prediction capabilities.
- Evaluate advanced customer segmentation techniques.
- Monitor changes in customer segment distribution over time.
- Expand dashboard reporting with additional customer KPIs.

## 14. Author

**Kirana B**

GitHub: [kirana-23](https://github.com/kirana-23)

---

*This project demonstrates the application of Python, SQL, RFM modelling, and Power BI to convert customer transaction data into actionable business intelligence.*
