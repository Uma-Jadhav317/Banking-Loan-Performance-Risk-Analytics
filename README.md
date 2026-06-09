# Banking-Loan-Performance-Risk-Analytics
End-to-end banking analytics project involving data cleaning, dimensional data modeling, KPI development, loan portfolio analysis, delinquency tracking, repayment analysis, and branch performance evaluation using MySQL.

## Overview

This project demonstrates the design and implementation of a Banking Analytics Data Warehouse using MySQL. The project transforms raw banking loan data into a structured analytical model to support loan portfolio monitoring, customer analytics, branch performance evaluation, credit risk assessment, and business intelligence reporting.

The solution follows a complete analytics workflow including data cleaning, ETL preparation, dimensional modeling, KPI development, and SQL-based business reporting.

---

## Project Highlights

### Banking Domain Analytics

* Loan Portfolio Analysis
* Credit Risk Assessment
* Delinquency Monitoring
* Customer Retention Analysis
* Branch Performance Evaluation
* Product Performance Analysis
* Customer Segmentation
* Loan Repayment Analytics


### Business Intelligence

* KPI Development
* Trend Analysis
* Executive Reporting
* Performance Monitoring
* SQL-Based Analytics
* Insight Generation

---

## Data Architecture

### Dimension Tables

#### dim_client

Contains customer demographic and credit information.

Key Attributes:

* Client ID
* Client Name
* Gender
* Age
* Income Range
* Employment Type
* Credit Score
* Customer Category

#### dim_branch

Contains branch-level information.

Key Attributes:

* Branch ID
* Branch Name
* Bank Name
* Region
* State
* City
* Branch Performance Category

#### dim_product

Contains loan product information.

Key Attributes:

* Product ID
* Product Code
* Purpose Category
* Loan Term
* Interest Rate
* Grade

---

### Fact Tables

#### fact_loan

Stores loan-level transactional data.

Key Metrics:

* Loan Amount
* Funded Amount
* Disbursement Date
* Loan Status
* Repayment Type

#### fact_repayment

Stores repayment performance data.

Key Metrics:

* Total Payment
* Principal Recovery
* Interest Recovery
* Delinquency Status
* Default Status
* Repayment Behavior

#### final_fact_loan

Integrated analytical fact table used for reporting and KPI calculations.

---

## Project Workflow

### Step 1: Data Cleaning

* Cleaned raw banking datasets using Microsoft Excel.
* Removed duplicate records.
* Standardized data formats.
* Performed data quality validation.
* Exported cleaned datasets as CSV files.

### Step 2: Database Development

* Created Banking Data Warehouse in MySQL.
* Built relational database schema.
* Designed dimension and fact tables.

### Step 3: Data Modeling

Implemented Star Schema Architecture:

Fact Tables:

* fact_loan
* fact_repayment
* final_fact_loan

Dimension Tables:

* dim_client
* dim_branch
* dim_product

### Step 4: SQL Analytics

Developed SQL queries for:

* Client Analytics
* Loan Analytics
* Repayment Analytics
* Branch Analytics
* Product Analytics
* Risk Analytics

### Step 5: Business Intelligence Reporting

Generated actionable insights to support:

* Lending Decisions
* Risk Monitoring
* Portfolio Management
* Branch Performance Tracking

---

## Key Performance Indicators (KPIs)

### Customer KPIs

* Total Clients
* Active Clients
* New Clients
* Client Retention Rate

### Loan KPIs

* Total Loan Amount
* Total Funded Amount
* Average Loan Size
* Loan Status Distribution

### Risk KPIs

* Delinquency Rate
* Default Rate
* Credit Score Distribution
* High-Risk Customer Analysis

### Repayment KPIs

* Total Repayment Amount
* Principal Recovery
* Interest Recovery
* Repayment Behavior Analysis

### Branch KPIs

* Branch Performance Category
* Region-wise Loan Distribution
* State-wise Loan Distribution
* Branch Funding Performance

---

## Tools & Technologies

* MySQL
* SQL
* Microsoft Excel
* CSV Processing
* Data Cleaning
* Data Validation
* Star Schema Modeling
* Business Intelligence
* Financial Analytics

---

## Key Skills Demonstrated

SQL • MySQL  • ETL • Data Cleaning • Data Modeling • Star Schema • Banking Analytics • Financial Analytics • Credit Risk Analysis • Loan Portfolio Analysis • KPI Reporting • Business Intelligence • Customer Segmentation • Data Validation • Reporting & Analytics

---

## Author

Uma Rathod

Data Analyst | SQL | Power BI | Tableau | Banking Analytics | Financial Analytics | Business Intelligence

LinkedIn: https://www.linkedin.com/in/umajadhavofficial

--- Screenshots

<img width="213" height="134" alt="image" src="https://github.com/user-attachments/assets/818ae185-84d9-438a-ab1a-d043265953b4" />
<img width="367" height="146" alt="image" src="https://github.com/user-attachments/assets/e3c991eb-44ed-4db6-afda-e46ad453b887" />
<img width="219" height="181" alt="image" src="https://github.com/user-attachments/assets/35b55f71-b914-4e8f-8239-e1d359f2bb66" />









