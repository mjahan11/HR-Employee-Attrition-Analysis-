# Key Columns: -

## Project Overview
This project aims to uncover the key drivers behind employee turnover within an organization. Using a dataset of 1,480 employees, it applies SQL analysis to identify patterns related to pay, work-life balance, and career growth. The objective is to generate data-driven insights that enable HR teams to adopt targeted “Surgical Retention” strategies, focusing on high-risk groups and minimizing the significant costs tied to hiring and training.
The work spans the full data analytics lifecycle, including data cleaning and preprocessing in Python, detailed exploratory and analytical querying with SQL, and the creation of interactive Power BI dashboards for effective and engaging visualization.

<img width="1024" height="558" alt="image" src="https://github.com/user-attachments/assets/409acfca-55f6-4508-bfbe-9fe7f52cd1bb" />

#  Dataset 
* **Source:** https://github.com/mjahan11/HR-Employee-Attrition-Analysis-/blob/main/HR_Analytics.csv
* **Description:** Contains 1,480 records of employee data, including demographics, job roles, compensation details, survey-based satisfaction scores, and historical tenure data to analyze workforce stability.


## Tech Stack

* **Data Processing:** Python (Pandas, NumPy)
* **Database:** SQL Server (SQL)
* **Visualization:** Power BI
* **Reporting:** Gamma (AI-powered presentation), Microsoft PowerPoint

##  Project Steps

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


## Key Results
 Insight : 
*  The organization experiences moderate attrition, primarily driven by employees in Research & Development and Sales departments with younger employees showing a higher tendency to leave.
*  Attrition is primarily driven by overtime, low job satisfaction, poor work-life balance, and frequent business travel, highlighting employee burnout and engagement issues.
*  Employees with longer commute distances, lower training exposure, and reduced job involvement show significantly higher attrition trends.
*   Attrition is strongly linked to compensation, with lower salary bands and lower job levels experiencing higher employee turnover.
*   Employees in early years or without recent promotions tend to leave more.

## FINAL SUMMARY:
To reduce attrition, the organization should focus on improving work-life balance, enhancing compensation, strengthening career growth opportunities, and increasing employee engagement, especially among early-career employees.

## Report Pages Screenshots
 EXECUTIVE OVERVIEW:
<img width="1034" height="659" alt="image" src="https://github.com/user-attachments/assets/f67a3522-d5a9-4cca-8784-a9f1abf90d5b" />

 ATTRITION Analysis:
<img width="975" height="543" alt="image" src="https://github.com/user-attachments/assets/4595008e-dd63-4981-82fa-08eec4df5bca" />

 WORK BEHAVIOR:
<img width="975" height="547" alt="image" src="https://github.com/user-attachments/assets/aed01237-38ed-4575-bff1-f7f3b954abe5" />

 Compensation Analysis:
<img width="975" height="549" alt="image" src="https://github.com/user-attachments/assets/50f82feb-647c-4cb9-b2d4-400c551d5ea2" />

 EXPERIENCE & GROWTH:
<img width="975" height="546" alt="image" src="https://github.com/user-attachments/assets/e34125ea-5c67-4c4c-9c34-9eeb71cc42b9" />


## Business Recommendations:
* Improve Work-Life Balance & Reduce Burnout :
Implement strict overtime monitoring policies and encourage flexible working hours / hybrid work. Reduce frequent travel where possible (use virtual meetings).

*  Enhance Employee Engagement & Job Satisfaction:
Conduct regular employee feedback surveys. Introduce recognition & reward programs. Improve manager-employee communication

*  Revise Compensation & Benefits Strategy:
Review and adjust salary structure for lower bands. Provide performance-based incentives. 

*  Strengthen Career Growth & Promotion Pathways:
Establish clear career progression paths and conduct regular promotion reviews. Provide internal mobility opportunities.

* Focus on Early-Career Employee Retention:
Improve onboarding programs and assign mentors for new employees. Provide early career development plans.

* Address Commute & Work Environment Challenges:
Offer remote/hybrid work options. Provide relocation or travel support. Introduce flexible shift timings

* Increase Training & Development Programs:
Increase training frequency and offer skill development programs. Align training with career growth goals


