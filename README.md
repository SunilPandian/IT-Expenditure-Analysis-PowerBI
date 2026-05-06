# 📊 IT Expenditure Analysis Dashboard | Power BI

## 📌 Project Overview

This project focuses on analyzing IT expenditure across different business areas, regions, and cost categories using Power BI.

The objective of this dashboard is to provide transparency into:
- Actual IT expenditure
- Forecasted spending
- Planned budget allocation
- Budget variance analysis
- Cost distribution across IT functions and regions

The dashboard helps identify:
- Overspending and underspending areas
- Major IT cost drivers
- Regional expenditure patterns
- Budget alignment across departments

---

# 🎯 Business Problem

Organizations often struggle to monitor and optimize IT expenditures across multiple departments and geographies.

Without centralized reporting:
- Budget overruns may go unnoticed
- Forecasting becomes inaccurate
- Operational inefficiencies remain hidden
- Financial accountability becomes difficult

This dashboard addresses these challenges by enabling interactive financial analysis and root-cause investigation.

---

# 🛠️ Tools & Technologies Used

- **Power BI** → Dashboard Development & Data Visualization
- **Power Query** → Data Cleaning & Transformation
- **DAX (Data Analysis Expressions)** → KPI & Variance Calculations
- **Excel** → Data Source

---

# 📂 Dataset Information

The dataset contains IT expenditure data categorized by:

- Business Area
- IT Area
- Region
- Country
- Cost Element Group
- Cost Element Sub Group
- Actual Spend
- Forecast Spend
- Planned Budget
- Monthly Expenditure Data

---

# ⚙️ Data Preparation Steps

The following transformations were performed using Power Query:

- Standardized column names
- Replaced null values with zero
- Validated numerical data types
- Created proper date fields for time-series analysis
- Structured data for interactive reporting

---

# 📈 Key KPIs & Metrics

The dashboard includes the following KPIs:

- Total Actual Spend
- Total Forecast Spend
- Total Planned Budget
- Budget Variance
- Variance Percentage

### DAX Measures Used

```DAX
Total Actual = SUM('Data'[Actual])

Total Forecast = SUM('Data'[Forecast])

Total Plan = SUM('Data'[Plan])

Actual vs Plan Variance =
[Total Actual] - [Total Plan]

Variance % =
DIVIDE(
    [Actual vs Plan Variance],
    [Total Plan]
)
```

---

# 📊 Dashboard Features

## 🔹 Executive Summary Page

Includes:
- KPI Cards
- Monthly IT Expenditure Trend
- Regional IT Spend Comparison
- IT Cost Distribution Treemap
- Interactive Slicers

### Key Insights
- Actual spend is significantly below planned budget
- USA contributes the majority of IT expenditure
- Labor is the largest IT cost driver
- Forecast and planned budgets remain stable across months

---

## 🔹 Detailed Variance Analysis Page

Includes:
- Variance Analysis Matrix
- Conditional Formatting
- Hierarchical Drilldowns
- Decomposition Tree for Root-Cause Analysis

### Key Insights
- Infrastructure has the highest IT expenditure
- Services and R&D show significant negative variance
- Labor and Infrastructure contribute heavily to budget gaps
- Root-cause analysis highlights operational inefficiencies

---

# 📌 Business Insights

### ✔ Budget Utilization Gap
Actual IT expenditure is significantly below planned budget levels, indicating possible delayed execution or phased spending.

### ✔ Labor Dominates IT Costs
Labor-related expenses form the largest share of IT expenditure.

### ✔ Regional Spending Concentration
The USA region contributes the majority of total IT spending.

### ✔ Infrastructure-Heavy Operations
Infrastructure-related functions consume substantial IT budget allocation.

---

# 🎨 Dashboard Screenshots

## Executive Summary

(Add screenshot here)

---

## Detailed Variance Analysis

(Add screenshot here)

---

# 📈 Project Workflow

1. Data Collection from Excel
2. Data Cleaning using Power Query
3. Data Modeling in Power BI
4. DAX Measure Creation
5. Dashboard Design & Visualization
6. Variance Analysis & Root-Cause Exploration
7. Business Insight Generation

---

# 🚀 Future Enhancements

- Forecast Accuracy Analysis
- Predictive Budget Modeling
- Drillthrough Pages
- Advanced Tooltip Reporting
- Role-Level Security (RLS)
- Automated Refresh Pipelines

---

# 💡 What I Learned

Through this project, I strengthened my understanding of:
- Financial KPI analysis
- Variance reporting
- Power BI dashboard design
- DAX calculations
- Interactive business storytelling
- Root-cause analytical techniques

---

# 👨‍💻 Author

## Sunil Pandian

🎯 Data Analyst | SQL | Excel | Power BI | Tableau | Python

I am a data-driven professional with 7+ years of experience at Amazon Development Centre, currently transitioning into a Data Analyst role.

My experience in customer operations and business processes has helped me develop strong analytical thinking and problem-solving skills using data-driven approaches.

---

# 🛠️ Technical Skills

### SQL
- Joins
- CTEs
- Window Functions
- Data Transformation

### Excel
- Pivot Tables
- KPI Analysis
- Dashboards
- Data Cleaning

### Power BI / Tableau
- Interactive Dashboards
- Data Visualization
- Business Reporting

### Python
- Pandas
- NLP
- Sentiment Analysis
- Data Analysis

---

# 📫 Contact Information

📧 Email: harleykingsunil@gmail.com

📍 Location: Karaikal, India

🔗 LinkedIn:  
https://www.linkedin.com/in/sunil-pandian-80b97427b/

💻 GitHub:  
https://github.com/SunilPandian

---

# ⭐ If you found this project useful, feel free to star the repository.
