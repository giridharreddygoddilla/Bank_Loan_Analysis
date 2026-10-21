# 🏦 Bank Loan Analytics — Excel Dashboard & Lending Performance

*Analyzing 38K+ loan applications to evaluate lending performance, repayment outcomes, and portfolio risk using interactive Excel dashboards.*

![Microsoft Excel](https://img.shields.io/badge/Excel-Dashboard-217346?logo=microsoftexcel&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-EDA-blue)
![Data Visualization](https://img.shields.io/badge/Data%20Visualization-Dashboards-orange)

## 1. 📌 Project Overview

Analyzed bank loan data to assess lending performance, repayment behavior, and portfolio quality. Developed interactive Excel dashboards to support performance monitoring and data-driven lending decisions.

## 2. 🎯 Business Questions & Objectives

- How are loan applications, disbursements, and repayments performing?
- What proportion of loans are classified as good versus bad?
- Which loan purposes and borrower characteristics dominate the portfolio?
- How do lending trends and repayment outcomes vary over time?

## 3. 📊 Key Findings & Insights

- **38,576** loan applications analyzed.
- **$435.76M** in total funded loans and **$473.07M** in total payments received.
- **86.18%** classified as good loans; **13.82%** as bad loans.
- **12.05%** average interest rate and **13.33%** average debt-to-income (DTI) ratio.
- **Debt consolidation** was the leading loan purpose, accounting for 18,214 applications (47.2%).
- Monthly applications increased from **2,332 in January** to **4,314 in December 2021**.

## 4. 💡 Business Recommendations

- Monitor charged-off loans and repayment collections to identify potential credit losses.
- Review loan-purpose and borrower-level patterns alongside repayment outcomes.
- Track monthly application growth against funding and portfolio quality.
- Analyze current loans separately from fully paid and charged-off loans.

## 5. 🖼️ Dashboard Preview & Key Visuals

The project includes three dashboard views:

- **Loan Performance Summary** — lending KPIs and loan-status comparisons.
- **Lending Trends & Portfolio Analysis** — monthly trends, geography, loan terms, employment, loan purpose, and home ownership.
- **Loan Data Explorer** — detailed loan and borrower-level exploration.

### Summary Dashboard

![Bank Loan Summary Dashboard](Images/Summary_Dashboard.png)

- This dashboard provides a high-level summary of key loan application metrics and lending performance.
- It highlights loan amounts, funded amounts, repayments, and good versus bad loan indicators.

### Overview Dashboard

![Bank Loan Overview Dashboard](Images/Overview_Dashboard.png)

- This dashboard presents detailed insights into loan applications across different categories and borrower profiles.
- It helps identify trends in loan status, loan purpose, employment length, and borrower home ownership.
## 6. 🛠️ Tools & Technical Skills

- **Microsoft Excel** — data analysis and interactive dashboard development
- **Exploratory Data Analysis (EDA)** — identifying patterns and trends
- **KPI Analysis** — measuring lending and repayment performance
- **Data Visualization** — presenting portfolio metrics
- **Business Analysis** — translating findings into actionable recommendations

## 7. ⚙️ Methodology & Analytical Workflow

1. Inspected the dataset structure and data quality.
2. Reviewed missing values, duplicate records, and loan identifiers.
3. Analyzed application volume, funded amounts, payments, interest rates, and DTI.
4. Compared good and bad loans and evaluated loan-status outcomes.
5. Examined monthly trends, loan purposes, and borrower characteristics.
6. Developed dashboard views and translated findings into business recommendations.

## 8. 📂 Dataset Overview

| Attribute | Details |
|---|---|
| Source file | `financial_loan.CSV` |
| Records | 38,576 |
| Columns | 25 |
| Reporting period | January–December 2021 |
| Missing data | 1,438 missing employment-title values |
| Duplicate rows | None identified |

## 9. 📁 Repository Structure

```text
bank-loan-analytics/
├── Analysis and Dashboard/
│   └── Bank Loan Analysis and Dashboard.xlsx
├── Business Problem/
│   └── Problem_Statement.docx
├── Data/
│   └── financial_loan.CSV
├── Images/
│   ├── Bank_Image.png
│   ├── Overview_Dashboard.png
│   └── Summary_Dashboard.png
└── README.md
```

## 10. 🚀 How to Run / Explore the Project

1. Clone or download this repository.
2. Open `Analysis and Dashboard/Bank Loan Analysis and Dashboard.xlsx` in Microsoft Excel.
3. Navigate through the dashboard sheets to explore lending KPIs, trends, and loan outcomes.
4. Refer to `data/financial_loan.CSV` for the underlying dataset.

## 11. ⚠️ Limitations & Assumptions

- The analysis reflects the supplied 2021 dataset, not current lending conditions.
- Total payments received are not equivalent to profit.
- Good/bad loan classifications follow the dataset's existing definitions.
- Observed patterns do not establish causation or constitute a validated credit-risk model.
- Verify dataset redistribution permissions before publishing the raw data.

---
