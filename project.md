**🏦 Loan Portfolio & Risk Analysis System Using SQL**


**📌 Project Overview**
The Loan Portfolio & Risk Analysis System is a SQL-based data analytics project designed to help financial institutions monitor, analyze, and manage their loan portfolios effectively.

This project focuses on loan performance, customer behavior, portfolio health, credit risk assessment, overdue payments, and business KPIs using SQL queries. The solution enables management to make data-driven lending and risk management decisions through structured database analysis.

<a href="https://github.com/Aniketyadav004/SQL-/blob/main/Loan_Portfolio%26Risk_Analysis%20.docx"> Project view</a>


🎯 **Business Problem**
Financial institutions handle thousands of loan applications across different cities, customer segments, and loan products. As loan volumes increase, management requires a centralized system to answer critical business questions such as:

Which customers have active loans?
Which loan products generate the highest business?
What is the total disbursed loan amount?
Which customers have overdue payments?
Which cities have the highest loan demand?
What is the current outstanding portfolio?
Which customers represent higher credit risk?
How is loan performance changing over time?



Problems
<a href="https://github.com/Aniketyadav004/SQL-/blob/main/%F0%9F%93%8C%20SQL%20Project.docx">Problems view</a>


This project provides SQL-based solutions to answer these business questions.


🗄️ **Database Schema**
**Loan Table**
The project is built around a single primary table:


**LOAN**
Column Name ,
Loan_ID ,
Customer_ ID ,
Customer_Name ,
Gender ,
Age ,
City ,
State ,
Employment_Type ,
Annual_Income ,
Loan_Type ,
Loan_Amount ,
Interest_Rate ,
Loan_Term ,
Application_Date ,
Approval_Date ,
Disbursement_Date ,
Loan_Status ,
Credit_Score ,
Monthly_EMI ,
Amount_Paid ,
Outstanding_Amount ,
Overdue_Amount ,
Payment_Status


📊 **Project Objectives**
Basic SQL Analysis,
Customer loan records,
Loan amount analysis,
Credit score filtering,
Income-based customer analysis,
Overdue payment tracking,
Filtering & Sorting,
Top loan amounts,
Customer ranking,
Loan status analysis,
Interest rate analysis,
Aggregate Analysis,
Total loan applications,
Total disbursement amount,
Outstanding balance,
Average loan amount,
Average credit score,
GROUP BY & HAVING Analysis,
Loan type analysis,
City-wise loan distribution,
Employment-based loan analysis,
Portfolio segmentation,
Risk Classification,
Customer risk categorization,
Credit score evaluation,
Outstanding amount by risk group,
Overdue amount by risk group,
Date Analysis,
Year-wise loan performance,
Monthly approvals,
Disbursement trends,
Application growth analysis,
Business KPI Analysis,
Loan Approval Rate,
Loan Rejection Rate,
Total Disbursement,
Total Outstanding Amount,
Default Rates,
Overdue Loan Percentage,
Advanced SQL Analysis,
Top borrowers,
Top cities by loan value,
Multiple loan holders,
Risky borrower identification,
Portfolio performance evaluation



⚠️**Risk Classification Logic**
Customers are categorized based on their credit score:

Credit Score	Risk Category,
750+	Low Risk,
650 - 749	Medium Risk,
550 - 649	High Risk,
Below 550	Very High Risk,
This classification helps identify potential default risks and outstanding portfolio exposure.



📈 **Key Business KPIs**
The project calculates and monitors:

Loan Approval Rate # 
Loan Rejection Rate #
Average Loan Amount #
Total Loan Portfolio Value #
Total Disbursed Amount #
Total Outstanding Amount #
Total Overdue Amount #
Average Credit Score #
Default Customer Count #
Percentage of Overdue Loans #


🛠️**Technologies Used**
SQL *
MySQL / PostgreSQL / SQL Server *
Aggregate Functions *
GROUP BY & HAVING *
CASE Statements *
Joins *
Subqueries *
Business KPI Analysis *
Data Analytics *


📂**Project Structure**
Loan-Portfolio-Risk-Analysis-System/

├── Database Design
├── Loan_Table.sql
├── Sample_Dataset.sql
├── Basic_SQL_Queries.sql
├── Filtering_Sorting.sql
├── Aggregate_Functions.sql
├── GroupBy_Having.sql
├── Case_Statements.sql
├── Date_Analysis.sql
├── Subqueries.sql
├── Advanced_SQL_Analysis.sql
├── KPI_Analysis.sql
└── README.md
