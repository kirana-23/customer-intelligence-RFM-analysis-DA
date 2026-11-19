# Customer Intelligence & RFM Analysis | Retail Analytics

\<p align="center">   \<img src="[https://img.shields.io/badge/Python-Data%20Analysis-blue?logo=python](https://img.shields.io/badge/Python-Data%20Analysis-blue?logo=python)" />   \<img src="[https://img.shields.io/badge/MySQL-SQL-orange?logo=mysql](https://img.shields.io/badge/MySQL-SQL-orange?logo=mysql)" />   \<img src="[https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi)" />   \<img src="[https://img.shields.io/badge/Dataset-500K%2B%20Transactions-success](https://img.shields.io/badge/Dataset-500K%2B%20Transactions-success)" /> \</p>

## 1. Project Overview

Understanding customer purchasing behaviour and identifying high-value customers are essential for improving business performance, customer retention, and revenue growth.

This project presents an end-to-end Retail Analytics solution using the **UCI Online Retail II dataset**, containing over 500K transactions.

The analysis combines Python-based data cleaning and exploratory data analysis, MySQL-based business queries, and Power BI dashboard development to investigate sales performance, product trends, geographical distribution, and customer purchasing behaviour.

A key component of the project is **RFM (Recency, Frequency, Monetary) Analysis**, which evaluates customers based on their purchasing activity and spending patterns to support customer segmentation and retention strategies.

The objective is to transform large-scale transactional data into meaningful business insights that support data-driven retail and customer management decisions.

## 2. Business Objectives

- Analyze overall retail sales and transaction patterns.
- Identify top-performing products based on sales performance.
- Examine sales distribution across geographical locations.
- Understand customer purchasing behaviour and spending patterns.
- Calculate Recency, Frequency, and Monetary metrics.
- Segment customers based on purchasing activity and value.
- Identify high-value, loyal, and at-risk customer groups.
- Develop actionable recommendations for customer retention and revenue optimization.

## 3. Dataset Overview

The project uses the **Online Retail II dataset from the UCI Machine Learning Repository**.

The dataset contains transactional records from a UK-based online retail business.

| Dataset Attribute | Description                                       |
| ----------------- | ------------------------------------------------- |
| Dataset           | UCI Online Retail II                              |
| Records           | 500K+ transactions                                |
| Data Type         | Retail transaction data                           |
| Business Domain   | E-commerce / Retail Analytics                     |
| Analysis Focus    | Sales, Products, Geography, Customer Segmentation |

**Key dataset attributes include:**

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

## 4. Technology Stack

| Technology | Application                               |
| ---------- | ----------------------------------------- |
| Python     | Data cleaning and exploratory analysis    |
| Pandas     | Data manipulation and transformation      |
| NumPy      | Numerical operations                      |
| Matplotlib | Data visualization                        |
| Seaborn    | Exploratory and statistical visualization |
| MySQL      | Database management and business queries  |
| Power BI   | Interactive retail analytics dashboard    |

## 5. Project Workflow

### 5.1 Data Cleaning and Preparation

Performed data preparation using Python to improve data quality and ensure consistency for downstream analysis.

Key activities include:

- Inspecting dataset structure and data types.
- Identifying and handling missing values.
- Examining duplicate transaction records.
- Reviewing invalid and inconsistent transaction values.
- Preparing date and numerical columns.
- Creating a cleaned dataset for further analysis.

### 5.2 Exploratory Data Analysis (EDA)

Conducted exploratory analysis to understand overall retail performance and purchasing patterns.

Analysis areas include:

- Overall sales performance.
- Transaction and order trends.
- Product-level sales distribution.
- Geographical sales distribution.
- Customer purchasing patterns.
- Revenue contribution across different categories.

### 5.3 MySQL Data Integration

Integrated the prepared retail data into MySQL for structured querying and business analysis.

The database workflow includes:

- Importing prepared retail data into MySQL.
- Organizing transactional data for querying.
- Executing SQL queries to extract business insights.
- Analyzing sales, products, geography, and customer-related metrics.

### 5.4 SQL-Based Business Analysis

Used SQL to perform business-oriented analysis on retail transactions.

Key analysis areas include:

- Sales performance analysis.
- Product-level revenue analysis.
- Customer purchasing behaviour.
- Geographical sales comparisons.
- Customer-level aggregations.
- RFM-related customer analysis.

### 5.5 RFM Analysis and Customer Segmentation

Applied the RFM framework to evaluate customer value and purchasing behaviour.

The analysis uses three fundamental metrics:

| Metric    | Definition                              | Business Interpretation                                     |
| --------- | --------------------------------------- | ----------------------------------------------------------- |
| Recency   | Time since the customer's last purchase | Indicates how recently a customer engaged with the business |
| Frequency | Number of purchases made by a customer  | Indicates customer purchasing frequency                     |
| Monetary  | Total amount spent by a customer        | Measures customer spending contribution                     |

RFM scoring provides a structured approach to grouping customers according to their purchasing behaviour.

Customer segmentation helps businesses identify valuable customers, recognize customers who may require retention efforts, and develop targeted marketing strategies.

### 5.6 Power BI Dashboard Development

Developed an interactive Power BI dashboard to present retail performance and customer intelligence insights.

The dashboard is organized into four analytical sections:

- **Sales Analysis:** Overall sales performance and revenue trends.
- **Product Analysis:** Product-level sales and purchasing patterns.
- **Geographical Analysis:** Sales distribution across countries and locations.
- **RFM Analysis:** Customer segmentation and purchasing behaviour.

## 6. Dashboard Preview

### Page 1 – Sales Analysis



### Page 2 – Product Analysis



### Page 3 – Geographical Analysis



### Page 4 – RFM Customer Segmentation



## 7. Key Business Analysis Areas

| Analysis Area         | Business Purpose                                   |
| --------------------- | -------------------------------------------------- |
| Sales Analysis        | Understand overall revenue performance             |
| Product Analysis      | Identify products contributing to sales            |
| Geographical Analysis | Evaluate sales distribution by location            |
| Recency Analysis      | Identify recently active and inactive customers    |
| Frequency Analysis    | Understand customer purchasing frequency           |
| Monetary Analysis     | Evaluate customer spending contribution            |
| RFM Segmentation      | Group customers based on purchasing behaviour      |
| Customer Intelligence | Support customer retention and marketing decisions |

## 8. Business Recommendations

- **Customer Retention:** Prioritize customers showing declining purchasing activity through targeted engagement campaigns.
- **Customer Loyalty:** Develop loyalty initiatives for frequent and high-value customers.
- **Targeted Marketing:** Create personalized promotions based on customer segments.
- **Product Strategy:** Use product performance analysis to support inventory and merchandising decisions.
- **Geographical Strategy:** Evaluate regional sales patterns to identify opportunities for market expansion.
- **Revenue Optimization:** Focus on customer groups and products that contribute meaningfully to business revenue.

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

### Step 3: Install Python Dependencies

```bash
pip install pandas numpy matplotlib seaborn mysql-connector-python
```

Install any additional libraries required by the Python scripts.

### Step 4: Download the Dataset

Download the UCI Online Retail II dataset from:

[UCI Online Retail II Dataset](https://archive.ics.uci.edu/dataset/502/online+retail+ii)

Place the downloaded dataset in your working directory and update the file path in `data_cleaning.py` as required.

### Step 5: Run Data Cleaning

```bash
python data_cleaning.py
```

### Step 6: Perform Exploratory Data Analysis

```bash
python eda_cleaned_retail_data.py
```

### Step 7: Import Data into MySQL

Configure your MySQL connection details in `import_data_mysql.py` and execute:

```bash
python import_data_mysql.py
```

### Step 8: Execute SQL Analysis

Open `analysis_queries.sql` in MySQL Workbench and execute the queries against the imported retail database.

### Step 9: Explore the Power BI Dashboard

Open `retail project.pbix` using Power BI Desktop to explore the four dashboard pages.

## 11. Project Deliverables

| File                         | Description                        |
| ---------------------------- | ---------------------------------- |
| `data_cleaning.py`           | Data cleaning and preparation      |
| `eda_cleaned_retail_data.py` | Exploratory data analysis          |
| `import_data_mysql.py`       | MySQL data import script           |
| `analysis_queries.sql`       | SQL business analysis              |
| `retail project.pbix`        | Interactive Power BI dashboard     |
| `page1_sales.png`            | Sales dashboard preview            |
| `page2_products.png`         | Product dashboard preview          |
| `page3_geography.png`        | Geographical dashboard preview     |
| `page4_rfm.png`              | RFM segmentation dashboard preview |

## 12. Future Enhancements

- Integrate customer lifetime value (CLV) analysis.
- Develop customer churn prediction models.
- Explore customer purchasing trends over time.
- Introduce advanced customer segmentation techniques.
- Build customer retention and cohort analysis.
- Enhance dashboard reporting with additional retail KPIs.

## 13. Author

**Kirana B**

GitHub: [kirana-23](https://github.com/kirana-23)

---

*This project demonstrates the practical application of Python, SQL, and Power BI in retail analytics, customer intelligence, and RFM-based customer segmentation to support data-driven business decisions.*
