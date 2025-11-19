# 🧾Customer Behavior Analysis
_Analyzing customer buying patterns and revenue contribution to uncover high-value segments and optimize sales strategy using Python, Excel, and Power BI._

---

## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#business-problem">Business Problem</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>
- <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>
- <a href="#research-questions--key-findings">Research Questions & Key Findings</a>
- <a href="#dashboard">Dashboard</a>
- <a href="#how-to-run-this-project">How to Run This Project</a>
- <a href="#final-recommendations">Final Recommendations</a>
- <a href="#author--contact">Author & Contact</a>

---

## 📌 Project Overview
This project analyzes customer purchasing behaviour to uncover spending patterns, frequency trends, and high-value buyer segments. The entire workflow — from data cleaning and preparation in Excel to interactive insight visualization in Power BI — is built to mirror real retail analytics practices and support revenue-focused decision making.

✅ Data Cleaning & Preparation (Excel): Cleaned the raw customer purchase dataset by fixing missing values, removing duplicates, standardizing columns, and preparing a stable base for analysis.

✅ Interactive Visualization (Power BI): Built a dynamic dashboard showing customer segments, contribution patterns, frequency trends, and category-wise insights through slicers, KPIs, and drill-down charts.

✅ Insights & Recommendations: Summarized all findings into a clear, actionable format to highlight high-value customer groups, buying trends, and improvement opportunities for business decisions.



---
<h2><a class="anchor" id="dataset"></a>Dataset</h2>

- CSV file located in `/data/` folder (cleaned_data)

---

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- Excel (Data Cleaning & Preparation)
- Power BI (Interactive Visualizations)
- GitHub

---
<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>

```
customer-behavior-analysis/
│
├── README.md
├── .gitignore
├── Customer Purchase Behavior Analysis Report.pdf
│
├── dashboard/                  # Power BI dashboard file
│   └── customer_purchase_behaviour_dashboard.pbix
```

---

<h2><a class="anchor" id="Analysis"></a>Exploratory Data Analysis (EDA)</h2>


**Purchase Trends Observed:**
- Revenue Range: Monthly revenue stable, no extreme spikes or abnormal drops. Peaks visible in April and July — consistent with seasonal buying, not anomalies.
- Category Contribution: Clothing ($25.7K) and Accessories ($18.6K) dominated sales, showing higher customer preference in these segments.

**Customer Behaviour Patterns**
- Gender Split: Female 54.4% vs Male 45.6% — slightly skewed but no disproportionate imbalance.
- Age Group Distribution: Smooth spread across 20–60 years, no unusual clustering around any single age bracket.

**Seasonal Trends**
- Spring: Highest seasonal revenue ($147.6K), aligning with expected consumer purchasing cycles.
- Summer & Fall: Moderate but stable demand — no abnormal dips or spikes.

---

<h2><a class="anchor" id="dashboard"></a>Dashboard</h2>

- Power BI Dashboard shows:
  - Product-wise Purchase Value
  - Monthly Revenue Trend
  - Season-wise Performance
  - State-wise Revenue Map
  - Gender Contribution
  - Age-Group Revenue
 
<img width="1324" height="742" alt="dashboard" src="https://github.com/user-attachments/assets/cd7851fb-5c01-43fd-90da-0dfa2ac8a0ab" />

---








































## 🛠️ How to Use This Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/amlanmohanty1/customer-trends-data-analysis-SQL-Python-PowerBI.git
   cd customer-trends-data-analysis-SQL-Python-PowerBI
   ```
2. **Open Customer_Shopping_Behavior_Analysis.ipynb notebook**

    This file contains:

      - Data Import

      - Data exploration

      - Data cleaning

      - Connection to SQL Database
  
3. **Load the data from Python notebook into MySQL/PostgreSQL/MS SQL Server**

      - Create a database in SQL

      - Run Python code to load data into SQL database
  
      - Open **customer_behavior_sql_queries.sql**
  
      - Answer Business Questions using SQL Queries 
      
4. **Connect the SQL Database to Power BI**

      - Open **customer_behavior_dashboard.pbix**
   
      - Create interactive dashboard in Power BI
  
6. **Create Project Report and Presentation**

      - Create project report
   
      - Build presentation deck using Gamma AI
