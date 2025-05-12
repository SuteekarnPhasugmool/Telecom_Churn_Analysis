# Telecom Customer Churn Analysis (Excel-Based)

This project presents a churn analysis for a fictitious telecom provider using a sample dataset from DataCamp. The analysis was performed entirely in Microsoft Excel and includes data manipulation, pivot table analysis, and an interactive dashboard.

---

## 🎯 Project Objective

The goal of this project is to analyze customer churn patterns and identify potential factors contributing to customer attrition using Microsoft Excel.

---

## 🛠 Tools Used

- Microsoft Excel  
- Excel formulas (`IF`, nested `IF`)  
- Pivot Tables and Charts  
- Conditional Formatting  
- Excel Dashboard Design

---

## 📌 Key Tasks & Features

### 1. Data Manipulation

**Customer Sheet:**
- Created a binary `Churned` column using the `IF` function (`Yes` → `1`, `No` → `0`).

**Aggregate Sheet:**
- Created `Demographics` column by grouping customers by age using nested `IF` function:
  - Under 30
  - Senior
  - Other
- Created `Grouped Consumption` column based on Avg Monthly GB Download using nested `IF` function:
  - 10 or more GB
  - Between 5 and 10 GB
  - Less than 5 GB

### 2. Pivot Table Analysis

**Customer Pivots:**
- Calculated KPIs:
  - Total Customers  
  - Churned Customers  
  - Churn Rate (%)  
- Analyzed churn reasons and visualized with bar charts.
- Explored churn categories to identify those with the highest proportion of churned customers.

**Churn Analysis:**
- Churn rate by age groups (Demographics) shown via pie chart.
- Detailed churn rate and number of customers by age brackets (19–88 in 10-year intervals) using clustered column and line chart.
- Churn rate by Unlimited Data Plan (Yes/No).
- Combined analysis of Unlimited Data Plan and Grouped Consumption shown in a stacked bar chart.
- Churn rate by state and International Plan with conditional formatting (Red-Yellow-Green scale).
- Churn rate by account length (in 12-month intervals) and contract type.

### 3. Dashboard
- Designed a clean, interactive Excel dashboard combining all visualizations and key metrics.
- Highlights actionable insights and trends in customer churn behavior.

---

## 🔎 Key Insights
- **Overall churn rate** is **26.86%**, with **1,796 out of 6,687** customers having churned.
- **Top churn reasons** are:
  - Competitor made better offer (16.87%)
  - Competitor had better devices (16.54%)
  - Attitude of support person (11.30%)
- **Demographic trends**:
  - **Senior customers** have the **highest churn rate (38.22%)**.
  - **Customers under 30** show the **lowest churn rate (23.00%)**.
- The **number of customers peaks at 39-48 age bracket** with a **churn rate of 25.04%**, whereas the **79-88 age bracket has the highest churn rate** despite **having the lowest number of customers**.
- **Unlimited Data Plan impact**:
  - Customers **with an unlimited plan tend to churn more** across all data usage groups, especially in the **"Less than 5 GB"** group with a **churn rate of 34.69%** compared to **12.31%** for those without unlimited data.
  - The **"Between 5 and 10 GB"** users without unlimited plans also show elevated churn (31.91%).
- **Competitor-related churn**:
  - Offers and devices from competitors account for the largest share of churn (35%+).
  - Customers are clearly sensitive to **value propositions from competitors**, highlighting a need for improved offers or loyalty incentives.
- **State-level with International Plan churn**:
  - Highest churn rates observed in **California (75%)**, **Indiana (66.67%)**, and **New Hampshire (62.5%)**.
  - States with the lowest churn include **Wisconsin**, **North Dakota**, **Rhode Island**, and **Idaho** (all at **25%**).


---

## 📁 Files Included
- `Telecom_Churn_Analysis.xlsx` — Full Excel workbook with data, pivot tables, visualizations, and dashboard.
- `Telecom_Churn_Analysis_Dashboard.png` - An image of the dashboard.

---

## ✅ Conclusion

This Excel-based project demonstrates how meaningful customer churn insights can be extracted using only spreadsheet tools. It’s an accessible and effective way to perform data analysis and present results in a visually compelling manner.
