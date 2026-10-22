# Bank-Loan-Data-Analysis Dashboard (Power BI)
An interactive Power BI dashboard that analyzes bank loan applications, funded amounts, repayments, interest rates and borrower risk (Good Loan vs Bad Loan) to help a lending institution monitor portfolio health and make better lending decisions.

**Project Overview**

This project turns raw bank loan data into a three-page interactive report. It tracks the key lending KPIs (applications, funded amount, amount received, average interest rate and average DTI), compares Month-to-Date (MTD) performance against the previous month (Month-over-Month, MoM), and separates the portfolio into Good Loans and Bad Loans so that risk is easy to see.

Objectives
Monitor the overall performance of the loan portfolio.
Track MTD and MoM trends for applications, funding and repayments.
Classify loans as Good or Bad and measure the share of each.
Understand lending patterns by state, purpose, term, employment length, home ownership and grade.
Give stakeholders a drill-down view of individual loan records.

**Dataset Summary**
Item	Details
Source	- Kaggle 
Records	- 38,576 loan applications
Period covered0	- 01 Jan 2021 – 12 Dec 2021 
Loan terms - 36 months, 60 months

**Features**

KPI cards for Total Loan Applications, Total Funded Amount, Total Amount Received, Average Interest Rate and Average DTI, each with its MTD and MoM value.
Good vs Bad Loan analysis using donut charts, percentages and a loan-status summary table.
Slicers / filters for State, Loan Purpose, Grade and Good vs Bad Loan.
Visual breakdowns by month (trend), term, employment length, loan purpose, home ownership and state (map).

**Tools & Technologies**
Power BI Desktop: data modeling and visualization
DAX: measures, calculated columns, calculated tables, time intelligence
Power Query (M): data loading and transformation
