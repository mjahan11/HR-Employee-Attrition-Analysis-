# Key Columns: -

## Project Overview

This project focuses on identifying the underlying factors that contribute to employee turnover (attrition) within an organization. By analyzing a dataset of 1,480 employees, the study leverages SQL to uncover patterns related to compensation, work-life balance, and career progression. The goal is to provide data-driven insights that help HR departments implement "Surgical Retention" strategies—targeting high-risk groups to reduce the multi-million dollar costs associated with recruitment and training.

The project covers the complete data analytics lifecycle, including data cleaning and preprocessing using Python, in-depth exploratory and analytical queries using SQL, and the development of interactive dashboards in Power BI for clear and impactful visualization.

<img width="1024" height="558" alt="image" src="https://github.com/user-attachments/assets/409acfca-55f6-4508-bfbe-9fe7f52cd1bb" />

# 📊 Dataset 
* **Source:** https://github.com/mjahan11/HR-Employee-Attrition-Analysis-/blob/main/HR_Analytics.csv
* **Description:** Contains 1,480 records of employee data, including demographics, job roles, compensation details, survey-based satisfaction scores, and historical tenure data to analyze workforce stability.


## 🛠️ Tech Stack

* **Data Processing:** Python (Pandas, NumPy)
* **Database:** SQL Server (SQL)
* **Visualization:** Power BI
* **Reporting:** Gamma (AI-powered presentation), Microsoft PowerPoint

## 🚀 Project Steps

### 1. Data Cleaning & Preparation (Python)

* Removing duplicates.
* Removing nulls.
* Dropping columns (Deciding which data is actually useful).
* Creating a numeric Attrition column (Changing the data format so the computer can read it).
* Exported cleaned data to `.csv` for database ingestion.

### 2.  Exploratory Data Analysis (EDA) using SQL
Exploratory Data Analysis was conducted to understand relationships between employee attributes and attrition.

* Imported cleaned HR dataset into SQL Server for analysis
* Imported HR dataset into SQL Server and performed exploratory data analysis
* Developed SQL queries to analyze attrition drivers including department, salary, overtime, job satisfaction, and work-life balance
* Identified key patterns showing higher attrition among low-paid, early-career, and highly overworked employees




### 3. Data Visualization (Power BI)

* Built a dynamic dashboard connecting directly to the SQL database.
Key visualizations included:

* EXECUTIVE OVERVIEW
* ATTRITION Analysis
* WORK BEHAVIOR
* Compensation Analysis
* EXPERIENCE & GROWTH
* FINAL SUMMARY


## 📈 Key Results


## Business Recommendations:
 🔷 Improve Work-Life Balance & Reduce Burnout :
• Implement strict overtime monitoring policies and encourage flexible working hours / hybrid work. Reduce frequent travel where possible (use virtual meetings).

🔷 Enhance Employee Engagement & Job Satisfaction:
• Conduct regular employee feedback surveys. Introduce recognition & reward programs. Improve manager-employee communication

🔷 Revise Compensation & Benefits Strategy:
• Review and adjust salary structure for lower bands. Provide performance-based incentives. 

🔷 Strengthen Career Growth & Promotion Pathways:
• Establish clear career progression paths and conduct regular promotion reviews. Provide internal mobility opportunities.

🔷 Focus on Early-Career Employee Retention:
• Improve onboarding programs and assign mentors for new employees. Provide early career development plans.

🔷 Address Commute & Work Environment Challenges:
• Offer remote/hybrid work options. Provide relocation or travel support. Introduce flexible shift timings

🔷 Increase Training & Development Programs:
• Increase training frequency and offer skill development programs. Align training with career growth goals


