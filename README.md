# Customer Intelligence & RFM Analysis | Retail Analytics

## 1. Project Overview

Understanding customer purchasing behaviour and identifying high-value customers are essential for improving business performance, customer retention, and revenue growth.

This project presents an end-to-end Retail Analytics solution using the **UCI Online Retail II dataset**, containing over 500K transactions.

Using Python, MySQL, and Power BI, the project analyzes retail transactions to uncover sales trends, product performance, geographical patterns, and customer purchasing behaviour.

A key component of this project is **RFM (Recency, Frequency, Monetary) Analysis**, which evaluates customers based on their purchasing activity and spending patterns to identify valuable customer segments and support targeted retention strategies.

The objective is to transform raw transactional data into actionable business insights that support data-driven retail and marketing decisions.

## 2. Business Objectives

- Analyze overall retail sales and transaction patterns.
- Identify top-performing products and revenue contributors.
- Examine geographical sales distribution.
- Understand customer purchasing behaviour and spending patterns.
- Calculate Recency, Frequency, and Monetary metrics.
- Segment customers based on purchasing activity and value.
- Identify high-value, loyal, and at-risk customer groups.
- Develop actionable recommendations for customer retention and revenue optimization.

## 3. Dataset Overview

The project uses the **Online Retail II dataset** from the UCI Machine Learning Repository.

The dataset contains transactional records from a UK-based online retail business.

| Attribute | Details |
|---|---|
| Dataset | UCI Online Retail II |
| Records | 500K+ transactions |
| Data Type | Retail transaction data |
| Domain | E-commerce / Retail Analytics |
| Analysis Focus | Sales, Products, Geography, Customer Segmentation |

**Key dataset attributes:**

- Invoice
- StockCode
- Description
- Quantity
- InvoiceDate
- Price
- Customer ID
- Country

These attributes support transaction-level analysis, sales calculations, geographical comparisons, and customer-level RFM calculations.

**Dataset Source:** [UCI Machine Learning Repository – Online Retail II](https://archive.ics.uci.edu/dataset/502/online+retail+ii)

## 4. Tools & Technologies

| Technology | Application |
|---|---|
| Python | Data cleaning and exploratory data analysis |
| Pandas | Data manipulation and transformation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| MySQL | Database management and SQL-based business analysis |
| Power BI | Interactive retail analytics dashboard |

## 5. Project Workflow

### 5.1 Data Cleaning and Preparation

Performed data preparation using Python to improve data quality and ensure consistency.

- Examined dataset structure and data types.
- Identified and handled missing values.
- Checked duplicate transaction records.
- Reviewed invalid and inconsistent transaction values.
- Prepared date and numerical columns.
- Generated a cleaned dataset for further analysis.

### 5.2 Exploratory Data Analysis (EDA)

Conducted exploratory analysis to understand retail performance and purchasing patterns.

Analysis areas included:

- Overall sales performance.
- Transaction and order trends.
- Product-level sales distribution.
- Geographical sales distribution.
- Customer purchasing patterns.
- Revenue contribution analysis.

### 5.3 MySQL Data Integration

Integrated the prepared retail data into MySQL for structured querying and business analysis.

- Imported cleaned retail data into MySQL.
- Organized transactional data for querying.
- Executed SQL queries to extract business insights.
- Analyzed sales, product, geographical, and customer-related metrics.

### 5.4 SQL-Based Business Analysis

Used SQL queries to perform business-oriented analysis.

Key analysis areas included:

- Sales performance analysis.
- Product-level revenue analysis.
- Customer purchasing behaviour.
- Geographical sales comparisons.
- Customer-level aggregations.
- RFM-related customer analysis.

### 5.5 RFM Analysis and Customer Segmentation

Applied the RFM framework to evaluate customer value and purchasing behaviour.

| Metric | Definition | Business Significance |
|---|---|---|
| Recency | Time since the customer's last purchase | Measures customer activity |
| Frequency | Number of purchases made by a customer | Measures purchasing frequency |
| Monetary | Total amount spent by a customer | Measures customer value |

RFM scoring provides a structured approach to grouping customers according to their purchasing behaviour.

The segmentation helps identify valuable customers, recognize customers requiring retention efforts, and support targeted marketing strategies.

### 5.6 Power BI Dashboard Development

Developed an interactive Power BI dashboard organized into four analytical sections:

- **Sales Analysis:** Overall sales performance and revenue trends.
- **Product Analysis:** Product-level sales and purchasing patterns.
- **Geographical Analysis:** Sales distribution across countries and locations.
- **RFM Analysis:** Customer segmentation and purchasing behaviour.

## 6. Power BI Dashboard Preview

The interactive dashboard presents retail performance and customer intelligence insights through four dedicated analytical pages.

### Page 1 – Sales Analysis

![Sales Analysis Dashboard](page1_sales.png)

### Page 2 – Product Analysis

![Product Analysis Dashboard](page2_products.png)

### Page 3 – Geographical Analysis

![Geographical Analysis Dashboard](page3_geography.png)

### Page 4 – RFM Customer Segmentation

![RFM Customer Segmentation Dashboard](page4_rfm.png)

## 7. Key Business Analysis Areas

| Analysis Area | Business Purpose |
|---|---|
| Sales Analysis | Understand overall revenue performance |
| Product Analysis | Identify products contributing to sales |
| Geographical Analysis | Evaluate sales distribution by location |
| Recency Analysis | Identify recently active and inactive customers |
| Frequency Analysis | Understand customer purchasing frequency |
| Monetary Analysis | Evaluate customer spending contribution |
| RFM Segmentation | Group customers based on purchasing behaviour |
| Customer Intelligence | Support retention and marketing decisions |

## 8. Business Recommendations

- **Customer Retention:** Develop targeted engagement campaigns for customers showing declining purchasing activity.
- **Customer Loyalty:** Introduce loyalty initiatives for frequent and high-value customers.
- **Targeted Marketing:** Create personalized promotions based on customer segments.
- **Product Strategy:** Use product performance analysis to support inventory and merchandising decisions.
- **Geographical Strategy:** Evaluate regional sales patterns to identify potential market opportunities.
- **Revenue Optimization:** Prioritize customer groups and products that contribute significantly to business revenue.

## 9. Repository Structure

```text
customer-intelligence-RFM-analysis-DA/
│
├── analysis_queries.sql
├── data_cleaning.py
├── eda_cleaned_retail_data.py
├── import_data_mysql.py
│
├── page1_sales.png
├── page2_products.png
├── page3_geography.png
├── page4_rfm.png
│
├── retail project.pbix
└── README.md
```

## 10. How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/kirana-23/customer-intelligence-RFM-analysis-DA.git
```

### Step 2: Navigate to the Project Directory

```bash
cd customer-intelligence-RFM-analysis-DA
```

### Step 3: Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn mysql-connector-python
```

### Step 4: Download the Dataset

Download the UCI Online Retail II dataset:

[UCI Online Retail II Dataset](https://archive.ics.uci.edu/dataset/502/online+retail+ii)

Place the downloaded dataset in your working directory and update the file path in `data_cleaning.py` if required.

### Step 5: Execute Data Cleaning

```bash
python data_cleaning.py
```

### Step 6: Perform Exploratory Data Analysis

```bash
python eda_cleaned_retail_data.py
```

### Step 7: Import Data into MySQL

Configure the database connection details in `import_data_mysql.py` and execute:

```bash
python import_data_mysql.py
```

### Step 8: Execute SQL Queries

Open `analysis_queries.sql` in MySQL Workbench and execute the queries against the imported retail database.

### Step 9: Explore the Power BI Dashboard

Open `retail project.pbix` using Power BI Desktop to explore the interactive retail analytics dashboard.

## 11. Project Deliverables

| File | Description |
|---|---|
| `data_cleaning.py` | Retail transaction data cleaning |
| `eda_cleaned_retail_data.py` | Exploratory data analysis |
| `import_data_mysql.py` | MySQL data import workflow |
| `analysis_queries.sql` | SQL business analysis queries |
| `retail project.pbix` | Interactive Power BI dashboard |
| `page1_sales.png` | Sales dashboard screenshot |
| `page2_products.png` | Product dashboard screenshot |
| `page3_geography.png` | Geographical dashboard screenshot |
| `page4_rfm.png` | RFM dashboard screenshot |

## 12. Future Enhancements

- Integrate Customer Lifetime Value (CLV) analysis.
- Develop customer churn prediction models.
- Explore customer purchasing trends over time.
- Introduce advanced customer segmentation techniques.
- Implement customer retention and cohort analysis.
- Enhance dashboard reporting with additional retail KPIs.

## 13. Author

**Kirana B**

GitHub: [kirana-23](https://github.com/kirana-23)

---

*This project demonstrates the practical application of Python, SQL, and Power BI in retail analytics, customer intelligence, and RFM-based customer segmentation to support data-driven business decisions.*
