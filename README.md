
# 🔍 Fraud Detection Analytics Case Study

> An end-to-end fraud analytics project demonstrating how SQL, Python, Power BI, and Tableau can be used to identify suspicious financial transactions, uncover fraud patterns, and generate actionable business insights.

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![SQL](https://img.shields.io/badge/SQL-Analytics-orange?logo=mysql)
![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-yellow?logo=powerbi)
![Tableau](https://img.shields.io/badge/Tableau-Visualization-blue?logo=tableau)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Project Overview

Financial fraud continues to be one of the biggest challenges in banking and fintech. This project simulates a real-world fraud investigation workflow where transaction data is analyzed to identify suspicious activities and support data-driven fraud prevention.

The project covers the complete analytics lifecycle:

- Data exploration
- Data cleaning
- Fraud pattern detection
- SQL analysis
- Dashboard development
- Business insight generation

---

## 🎯 Objectives

- Detect potentially fraudulent transactions
- Analyze customer and transaction behavior
- Identify high-risk locations and time periods
- Discover unusual spending patterns
- Build interactive dashboards for fraud monitoring
- Demonstrate an end-to-end analytics workflow

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Data Cleaning & Analysis |
| Pandas | Data Manipulation |
| NumPy | Numerical Processing |
| Matplotlib | Data Visualization |
| SQL | Data Querying |
| Power BI | Interactive Dashboard |
| Tableau | Business Intelligence Dashboard |
| Excel | Data Inspection |

---

# 📂 Project Structure

```
Fraud-Detection-Analytics/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── python/
│   ├── data_cleaning.py
│   ├── fraud_analysis.py
│   └── visualization.py
│
├── sql/
│   ├── exploratory_queries.sql
│   ├── fraud_metrics.sql
│   └── risk_analysis.sql
│
├── powerbi/
│   └── Fraud Detection Dashboard.pbix
│
├── tableau/
│   └── Fraud Dashboard.twbx
│
├── exports/
│
├── docs/
│
└── README.md
```

---

# 📊 Key Analysis Performed

### Transaction Analysis

- Total Transactions
- Fraud vs Non-Fraud Distribution
- Transaction Value Analysis
- Average Transaction Amount
- Peak Transaction Hours

### Customer Analysis

- High-risk Customers
- Repeat Fraud Attempts
- Spending Behaviour
- Customer Segmentation

### Geographic Analysis

- Fraud by Region
- Location-Based Risk
- Cross-Border Transactions
- Suspicious Location Changes

### Time-Series Analysis

- Fraud Trends Over Time
- Daily Activity
- Weekly Patterns
- Monthly Fraud Rate

---

# 🧠 Fraud Indicators Investigated

- Large transaction amounts
- Multiple transactions in short intervals
- Location anomalies
- Repeated card usage
- Failed login attempts
- High-risk merchant categories
- Rapid account activity
- Unusual spending behaviour

---

# 📈 Dashboard Features

## Power BI Dashboard

- Executive KPI Summary
- Fraud Rate
- Transaction Volume
- Geographic Fraud Map
- Time-based Trends
- Interactive Filters
- Customer Risk Analysis

## Tableau Dashboard

- Fraud Distribution
- Transaction Analysis
- Risk Score Visualization
- Customer Segmentation
- Interactive Drill-down Analysis

---

# 🐍 Python Workflow

The Python scripts perform:

- Data Cleaning
- Missing Value Handling
- Duplicate Removal
- Feature Engineering
- Fraud Flag Detection
- Statistical Analysis
- Data Visualization

Run a script:

```bash
python fraud_analysis.py
```

---

# 🗄 SQL Analysis

SQL queries are used for:

- Fraud Detection
- Customer Analysis
- Aggregations
- Risk Scoring
- Outlier Detection
- KPI Calculation
- Business Reporting

Example:

```sql
SELECT
    transaction_type,
    COUNT(*) AS fraud_count
FROM transactions
WHERE fraud_flag = 1
GROUP BY transaction_type;
```

---

# 📊 Sample Business KPIs

- Total Transactions
- Total Fraud Cases
- Fraud Rate (%)
- Average Transaction Value
- High-Risk Customers
- Fraud by Region
- Fraud by Channel
- Peak Fraud Hours
- Monthly Fraud Trend
- Top Merchant Categories

---

# 📷 Dashboard Preview

> *(Add screenshots here)*

```
dashboard_screenshot_1.png

dashboard_screenshot_2.png

tableau_dashboard.png
```

---

# 🚀 How to Run

### 1. Clone Repository

```bash
git clone https://github.com/yourusername/fraud-detection-analytics.git
```

### 2. Install Python Packages

```bash
pip install pandas numpy matplotlib
```

### 3. Run Python Analysis

```bash
python fraud_analysis.py
```

### 4. Execute SQL Queries

Run the SQL scripts using:

- SQL Server Management Studio
- MySQL Workbench
- PostgreSQL
- DBeaver

### 5. Open Dashboards

- Open `.pbix` in **Power BI Desktop**
- Open `.twbx` in **Tableau Desktop**

---

# 📚 Skills Demonstrated

- Fraud Analytics
- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis (EDA)
- Business Intelligence
- Dashboard Design
- SQL Query Optimization
- KPI Reporting
- Data Visualization
- Financial Analytics
- Risk Analysis
- Storytelling with Data

---

# 💼 Business Value

This project demonstrates how analytics can help organizations:

- Detect fraudulent activities earlier
- Reduce financial losses
- Improve fraud monitoring
- Support compliance reporting
- Enable data-driven decision-making
- Enhance customer security

---

# 🎯 Learning Outcomes

By completing this project, you will gain hands-on experience with:

- Real-world fraud analytics
- SQL for business analysis
- Python for data processing
- Power BI dashboard development
- Tableau visualization
- Financial transaction analysis
- Risk assessment techniques

---

# 📄 License

This project is intended for educational and portfolio purposes.

---

## 👩‍💻 Author

**Deblina Mandal**

- 💼 Aspiring Data Analyst | Business Analyst
- 🐍 Python | SQL | Power BI | Tableau | Excel

**GitHub:** https://github.com/deblinamandal2002/

**LinkedIn:** https://www.linkedin.com/in/deblina-mandal-615507273/

---

⭐ If you found this project useful, consider giving it a **Star** on GitHub!
