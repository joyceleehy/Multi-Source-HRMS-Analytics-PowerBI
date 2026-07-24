# Multi-Source HRMS Workforce Analytics Dashboard | Power BI, SQL & Power Query

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=flat&logo=microsoft&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-F2C811?style=flat&logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat)

An end-to-end **Business Intelligence workforce analytics project** demonstrating how multiple HRMS data sources can be consolidated, transformed, and analysed using **Power Query, SQL, and Power BI** to deliver workforce insights across headcount, attrition, hiring trends, workforce costs, and planning metrics.

---

# Business Problem

HR teams often manage employee information across multiple systems, making it difficult to create a single source of truth for workforce reporting.

This project simulates a real-world HR analytics scenario where two separate HRMS files are consolidated into one master workforce dataset to support data-driven decision-making.

The dashboard helps HR stakeholders monitor:

- Workforce size and composition
- Active vs terminated employees
- Attrition trends
- Hiring patterns
- Workforce cost and budget variance
- Future workforce planning insights

---

# Dataset

**Source:** Synthetic HRMS datasets created for portfolio demonstration.

No real employee data was used.

## Data Sources

```
hrms_a.csv               HRMS source file A
hrms_b.csv               HRMS source file B
cleaned_master_data.csv  Final consolidated workforce dataset
```

## Data Coverage

The dataset includes:

- Employee demographics
- Department information
- Employment status
- Salary and workforce cost data
- Hiring and termination records
- Department-level workforce metrics

---

# Tools & Technologies

- **Power BI** – Data modeling, DAX measures, dashboard development
- **Power Query** – Data extraction, transformation, cleaning, and consolidation
- **SQL (SQLite)** – Workforce analysis, KPI calculation, trend analysis
- **Excel / CSV** – Source data management
- **Git & GitHub** – Version control and documentation

---

# Data Pipeline

```text
HRMS Source File A + HRMS Source File B
                    ↓
        Power Query Data Transformation
                    ↓
   Standardisation, Cleaning & Data Validation
                    ↓
             Master Workforce Dataset
                    ↓
              SQL Analysis Layer
                    ↓
        DAX Measures & KPI Calculations
                    ↓
             Power BI Dashboard
                    ↓
        Workforce Insights & Decisions
```

---

# Dashboard Preview

## Page 1 — Workforce Overview

Provides a high-level workforce summary including:

- Total headcount
- Active vs terminated employees
- Department distribution
- Hiring trends
- Workforce composition

![Workforce Overview](https://raw.githubusercontent.com/joyceleehy/hrms-workforce-analytics/main/images/dashboard.png)


---

## Page 2 — Attrition Analysis

Analyses employee turnover patterns including:

- Overall attrition rate
- Voluntary vs involuntary exits
- Department-level attrition
- Exit trends over time

![Attrition Analysis](https://raw.githubusercontent.com/joyceleehy/hrms-workforce-analytics/main/images/Attrition.png)


---

## Page 3 — Budget vs Actual

Evaluates workforce cost performance:

- Actual workforce cost
- Planned budget
- Budget variance
- Department-level cost comparison

![Budget vs Actual](https://raw.githubusercontent.com/joyceleehy/hrms-workforce-analytics/main/images/Budget.png)


---

## Page 4 — Forecast Insights

Supports workforce planning through:

- Hiring movement analysis
- Exit trends
- Workforce changes over time
- Future planning indicators

![Forecast Insights](https://raw.githubusercontent.com/joyceleehy/hrms-workforce-analytics/main/images/forecast.png)

---

# Key Business Insights

## Workforce Distribution

- Analysed workforce composition across departments to identify employee distribution patterns and workforce structure.

## Attrition Analysis

- Identified departments with higher employee turnover trends, helping highlight potential retention risks.

## Workforce Cost Management

- Compared actual workforce costs against planned budgets to identify cost variance and support financial planning.

## Workforce Planning

- Analysed hiring and termination patterns to provide visibility into workforce movement and future staffing needs.

---

# Power Query Data Cleaning & Transformation

Performed data preparation steps including:

- Loaded and combined multiple HRMS source files
- Standardised column names across datasets
- Cleaned employee ID formats into consistent standards
- Converted hire and termination dates into proper date formats
- Standardised department naming conventions
- Removed duplicate employee records
- Converted salary and cost fields into numeric formats
- Created employee status classification:
  - Active
  - Terminated
- Generated a consolidated master workforce dataset

---

# SQL Analysis Layer

SQL was used to perform workforce analysis and KPI calculations.

| SQL Technique | Application |
|---|---|
| Window Functions | Salary ranking by department |
| Running Totals | Cumulative hiring and exit trends |
| Moving Averages | Workforce trend analysis |
| Time-Series Analysis | Monthly workforce movement |
| Variance Analysis | Budget vs actual workforce cost |
| Cohort Analysis | Hiring and exit patterns by year |

---

# Data Model

The Power BI data model uses the cleaned master workforce dataset to support:

- Employee-level analysis
- Department-level reporting
- Workforce cost analysis
- Attrition tracking
- Hiring trend analysis

Relationships and calculated measures were created using Power BI data modeling and DAX.

---

# Skills Demonstrated

## Business Intelligence

- KPI Dashboard Development
- Workforce Reporting
- Executive Reporting
- Data Visualization
- Business Insights Generation

## Data Analytics

- Data Cleaning
- Data Validation
- Data Consolidation
- Trend Analysis
- Workforce Analytics
- Attrition Analysis

## Technical Skills

- Power BI
- Power Query
- DAX
- SQL
- SQLite
- Excel / CSV

---

# Future Improvements

- Connect to cloud-based HR data warehouse
- Automate scheduled HR reporting refreshes
- Add predictive attrition modelling
- Implement employee segmentation analysis
- Create automated executive reporting packs

---

# About Me

**Joyce Lee How Yee**

PL-300 Certified Business Intelligence & Data Analyst with experience in **People Analytics, HR reporting, Power BI, SQL, Python, and data visualization**. Passionate about transforming complex data into actionable business insights.

Currently open to:

- Business Intelligence Analyst roles
- Data Analyst roles
- People Analytics roles
- Reporting Analyst roles

📎 LinkedIn: https://www.linkedin.com/in/joyceleehowyee/

📎 GitHub Portfolio: https://github.com/joyceleehy
