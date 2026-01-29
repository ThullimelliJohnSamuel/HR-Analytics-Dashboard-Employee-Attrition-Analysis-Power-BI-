# 📊 HR Analytics Dashboard – Employee Attrition Analysis (Power BI)

## Project Overview
This project involves building an interactive HR Analytics dashboard using Power BI to analyze employee attrition and workforce trends. The dashboard helps identify attrition patterns across key employee attributes such as age, gender, education, job role, salary range, and years at the company.

## Dataset
- Format: CSV  
- Type: Sample HR employee dataset  
- Total Employees Analyzed: 1,470  

## Data Cleaning & Transformation
Data preparation was performed using Power Query with the following steps:
- Removed a column containing only null values
- Identified and removed 15 duplicate records based on Employee ID
- Replaced inconsistent values in categorical columns for standardization
- Converted all columns to appropriate data types (text, numeric, date)
- Created a new calculated column “Attrition Count” where Attrition = Yes was assigned 1 and Attrition = No was assigned 0 to enable accurate KPI calculations

## KPIs Developed
- Total Employee Count  
- Total Attrition Count  
- Attrition Rate (%)  
- Average Age  
- Average Salary  
- Average Years at Company  

## Dashboard Insights
The dashboard provides insights into employee attrition by:
- Gender  
- Age Group  
- Education Background  
- Job Role  
- Salary Range  
- Years at Company  

Interactive slicers allow department-wise analysis across HR, R&D, and Sales.

## Tools & Technologies
- Power BI  
- Power Query  
- DAX  
- CSV Dataset  

## Dashboard Preview
(Add the dashboard image in the repository and link it here)

## Key Learnings
- Hands-on experience in data cleaning and transformation using Power Query
- Creating calculated columns and KPIs for HR analytics
- Designing interactive Power BI dashboards for business insights
- Understanding workforce and attrition analysis from an HR perspective
