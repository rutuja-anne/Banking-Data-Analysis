# Banking Data Analysis Project (Power BI)

## 📌 Problem Statement

In the financial sector, understanding customer behavior, loan distribution, and deposit patterns is crucial for decision-making. This project aims to analyze a bank’s performance across various dimensions such as loan types, deposit accounts, client segmentation, and banking relationships using Power BI.

## 🎯 Objective

To build an interactive Power BI dashboard that provides:

- Insights into **Total Loans, Deposits, and Accounts**
- Gender-based and occupation-based loan and deposit analysis
- Relationship-wise breakdown (Commercial, Institutional, Private Bank, Retail)
- Tracking of income band and nationality-based behavior
- Fee income and business lending overview
- Summary insights for strategic decisions

## 🔍 Data Overview

- **Clients Data**: Gender, Occupation, Joining Year, Investment ID, Nationality
- **Loan Data**: Business Lending, Bank Loan, Credit Card Balance
- **Deposit Data**: Checking, Saving, Bank Deposit
- **Fee Metrics**: Processing Fees, Foreign Currency Usage, Engagement Accounts

## 🧠 My Approach

### 1. **Data Cleaning & Transformation**
- Cleaned and filtered the data inside Power BI using **Power Query Editor**
- Ensured consistency in units (e.g., M, Bn) for readability
- Created calculated columns & measures for:
  - `Processing Fees`
  - `Total Amount = Deposit + Loan`
  - `Gender-Based and Occupation-Based Metrics`

### 2. **EDA (Performed earlier in Google Colab)** [*Lost due to account reset*]
- Briefly explored:
  - Distribution of account types
  - Outlier detection in loan values
  - Correlation between deposits and income bands

### 3. **Dashboard Design in Power BI**
Created 4 report pages:
- **Home Page**: Overview of total metrics with slicers for Gender and Year
- **Loan Analysis**: Drill-down by occupation, banking relationship, and income band
- **Deposit Analysis**: Breakdown of deposits by occupation, nationality, and income band
- **Summary Page**: Unified view of all metrics, including fees, engagement, and foreign currency

## 📊 Dashboard Preview

### Home Page
![Home]![Screenshot 2025-06-19 125633](https://github.com/user-attachments/assets/17da7094-5ac8-4762-8ec6-f0c1a0862426)


### Loan Analysis
![Loan Analysis]![Screenshot 2025-06-19 125731](https://github.com/user-attachments/assets/bede6c23-45cd-4c30-883f-fa69539c8743)


### Deposit Analysis
![Deposit Analysis]![Screenshot 2025-06-19 125751](https://github.com/user-attachments/assets/982edb50-0921-4497-9669-88122e2823b0)


### Summary
![Summary]![Screenshot 2025-06-19 125810](https://github.com/user-attachments/assets/990b6fb1-ba22-4588-897f-a65d41dc00d1)


## 🧾 Key Learnings

- Designed **interactive visual reports** using slicers, cards, pie charts, and bar charts
- Learned advanced **DAX formulas** for business KPIs like processing fee and income segmentation
- Improved understanding of how **Power BI can aid financial decision making**

## 🚀 Tools Used

- **Power BI Desktop**
- Power Query (for transformation)
- DAX
- (Previously: Google Colab for EDA using Python, Pandas, Seaborn)

---

## 📂 How to Use

1. Clone the repo or download the files.
2. Open the `.pbix` file in Power BI Desktop.
3. Explore the report tabs and use slicers for dynamic filtering.

---


