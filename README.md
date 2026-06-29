# 💰 Loan Default Analysis Dashboard | SQL + Power BI

---

## 📌 Project Overview

This project demonstrates an end-to-end **Loan Default Analysis Dashboard** built using **SQL** and **Microsoft Power BI**. The objective is to transform raw loan application data into meaningful business insights that help financial institutions understand customer behavior, monitor loan performance, and identify default risk.

The workflow begins by importing the raw dataset into **SQL**, where the data is prepared and validated. The processed data is then imported into **Power BI** for analysis. Additional calculated columns such as **Year**, **Age Group**, **Credit Score Bins**, and **Income Bracket** were created to support deeper business analysis.

Using DAX, several KPIs including Default Rate, Year-over-Year (YOY) Growth, Year-to-Date (YTD) Loan Amount, Median Loan Amount, and Average Income were developed. The final dashboard consists of three interactive report pages that provide a comprehensive overview of loan performance and financial risk.

---

# 🎯 Project Objectives

* Analyze total loan distribution across different loan purposes.
* Monitor loan default trends.
* Compare average income by employment type.
* Evaluate loan amount by age group.
* Measure default rate across employment categories.
* Analyze customer demographics using education, marital status, and credit score.
* Calculate Year-over-Year (YOY) loan growth.
* Calculate Year-over-Year (YOY) default growth.
* Perform Year-to-Date (YTD) loan analysis.
* Generate actionable business insights for financial decision-making.

---

# 📂 Dataset Information

The dataset contains loan application records and applicant financial information.

### Original Dataset Columns

* LoanID
* Age
* Income
* LoanAmount
* CreditScore
* MonthsEmployed
* NumCreditLines
* InterestRate
* LoanTerm
* DTIRatio
* Education
* EmploymentType
* MaritalStatus
* HasMortgage
* HasDependents
* LoanPurpose
* HasCoSigner
* Default
* Loan_Date_DD_MM_YYYY

### Additional Columns Created

To improve analysis, the following calculated columns were created:

* Year
* Month
* Age Group
* Credit Score Bins
* Income Bracket

---

# 🗄 Data Model

This project uses a **single-table analytical model**.

```
Raw Dataset
      │
      ▼
SQL Database
      │
      ▼
Data Cleaning & Validation
      │
      ▼
Power BI
      │
      ▼
Calculated Columns
      │
      ▼
DAX Measures
      │
      ▼
Interactive Dashboard
```

---

# 📊 Key Performance Indicators (KPIs)

* Total Loan Amount
* Average Loan Amount
* Median Loan Amount
* Average Income
* Loan Amount by Purpose
* Default Rate (%)
* Default Rate by Employment Type
* Default Rate by Year
* Average Loan Amount by Age Group
* Total Loan by Credit Score
* Number of Loans by Education
* YOY Loan Amount Change
* YOY Loan Default Change
* YTD Loan Amount
* High Credit Score Loan Analysis

---

# ⚙️ DAX Measures Used

| Measure                                 | Purpose                                                    |
| --------------------------------------- | ---------------------------------------------------------- |
| Loan Amount by Purpose                  | Calculates total loan amount by loan purpose               |
| Average Income by Employment Type       | Calculates average income for each employment category     |
| Default Rate (%) by Employment Type     | Calculates employment-wise default percentage              |
| Average Loan Amount by Age Group        | Computes average loan amount by age group                  |
| Default Rate (%) by Year                | Calculates yearly default percentage                       |
| Median Loan Amount by Credit Score Bins | Finds median loan amount for each credit score category    |
| Average Loan Amount (High Credit Score) | Average loan amount for applicants with high credit scores |
| Total Loan (Adults)                     | Total loan amount for adult applicants                     |
| Number of Loans by Education            | Counts loans based on education category                   |
| YOY Loan Amount Change                  | Calculates Year-over-Year loan growth                      |
| YOY Loan Default Change                 | Calculates Year-over-Year default growth                   |
| YTD Loan Amount                         | Calculates Year-to-Date loan amount                        |

---

# 🛠 Tools & Technologies

* SQL
* Microsoft Power BI
* Power Query
* DAX
* Data Modeling
* Data Cleaning
* Data Transformation
* Microsoft Excel
* Git & GitHub

---

# 📈 Dashboard Features

## 📄 Page 1 — Loan Default & Overview

* Loan Amount by Purpose
* Average Income by Employment Type
* Default Rate by Employment Type
* Average Loan Amount by Age Group
* Default Rate by Year

---

## 📄 Page 2 — Applicant Demographics & Financial Profile

* Median Loan Amount by Credit Score Category
* Average Loan Amount (High Credit Score)
* Total Adult Loan by Credit Score
* Number of Loans by Education Type

---

## 📄 Page 3 — Financial Risk Metrics

* Year-over-Year Loan Amount Change
* Year-over-Year Default Change
* Year-to-Date Loan Amount
* Income Bracket Analysis
* Employment Type Analysis

---

# 📷 Dashboard Preview

## Loan Default & Overview

```md
![Loan Default Dashboard](https://github.com/Baibhavraj062/Loan-Default-Analysis-Dashboard-SQL-Power-BI/blob/main/Snapshot_1.png)
```

---

## Applicant Demographics & Financial Profile

```md
![Applicant Demographics](https://github.com/Baibhavraj062/Loan-Default-Analysis-Dashboard-SQL-Power-BI/blob/main/Snapshot_2.png)
```

---
## Financial Risk Metrics

```md
![Financial Risk Metrics](https://github.com/Baibhavraj062/Loan-Default-Analysis-Dashboard-SQL-Power-BI/blob/main/Snapshot_3.png)
```

---

# 💡 Business Insights

* Home loans account for the highest loan amount among all loan purposes.
* Full-time employees have the lowest default rate.
* Unemployed applicants exhibit the highest default risk.
* Adult applicants receive the highest average loan amount.
* Applicants with high credit scores generally qualify for larger loan amounts.
* Bachelor's degree holders account for the highest number of loan applications.
* YOY analysis highlights changes in loan disbursement and default trends.
* YTD analysis helps monitor loan performance throughout the year.
* Income segmentation enables lenders to identify high-value customer groups.

---

# 🚀 Skills Demonstrated

* SQL Querying
* Data Cleaning
* Data Transformation
* Power Query
* DAX Calculations
* Time Intelligence (YOY & YTD)
* Data Modeling
* KPI Development
* Dashboard Design
* Data Visualization
* Business Intelligence
* Financial Risk Analysis
* Analytical Thinking
* Business Insight Generation

---

# ✅ Conclusion

This project demonstrates the complete business intelligence workflow using **SQL** and **Power BI**. Starting from raw loan data, the project covers data preparation, transformation, DAX-based calculations, dashboard development, and business insight generation.

The dashboard provides valuable information about loan distribution, customer demographics, employment trends, credit score analysis, and default behavior. These insights can help financial institutions improve lending decisions, reduce credit risk, and monitor overall portfolio performance.

Overall, this project showcases practical skills in SQL, Power BI, DAX, data visualization, and business analytics, making it a strong portfolio project for aspiring Data Analysts.

---

# 👨‍💻 Created By

## **Baibhav Raj**

**Aspiring Data Analyst**

### Skills

* SQL
* Power BI
* DAX
* Microsoft Excel
* Data Cleaning
* Data Visualization
* Business Intelligence
* Data Analytics

---

⭐ **If you found this project useful, please consider giving this repository a Star!**
