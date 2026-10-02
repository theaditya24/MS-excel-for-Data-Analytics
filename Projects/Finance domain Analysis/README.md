# 🏦 Bank Loan Analysis | Finance Domain

An interactive **Bank Loan Analysis Dashboard** built using **Microsoft Excel** to analyze loan applications, funded amounts, repayments, interest rates, borrower characteristics, and loan quality.

This project focuses on transforming raw financial data into meaningful business insights through **data cleaning, KPI analysis, Excel formulas, Pivot Tables, charts, slicers, and interactive dashboards**.

---

## 📊 Project Overview

The objective of this project is to analyze the performance of a bank's loan portfolio and understand:

- Loan application trends
- Funded loan amounts
- Amount received from borrowers
- Interest rate performance
- Debt-to-Income (DTI) ratio
- Good vs Bad loan performance
- Loan purpose distribution
- Loan term distribution
- Employment length
- Home ownership
- State-wise loan applications
- Monthly loan application trends

The project contains two major dashboards:

1. **Summary Dashboard**
2. **Overview Dashboard**

---

## 🖥️ Dashboard Preview

### 📌 Summary Dashboard

The Summary Dashboard provides a high-level view of the overall loan portfolio and separates loans into **Good Loan** and **Bad Loan** categories.

![Bank Loan Dashboard](dashboard%20img/dashboard.png)

### 📌 Overview Dashboard

The Overview Dashboard provides a detailed analysis of loan applications across different dimensions such as month, state, loan term, employment length, loan purpose, and home ownership.

![Bank Loan Summary](dashboard%20img/summary.png)

---

## 🎯 Key KPIs

The dashboard tracks the following major financial KPIs:

| KPI | Description |
|---|---|
| **Total Loan Applications** | Total number of loan applications |
| **Total Funded Amount** | Total amount funded by the bank |
| **Total Amount Received** | Total amount received from borrowers |
| **Average Interest Rate** | Average interest rate across loans |
| **Average DTI** | Average Debt-to-Income ratio |
| **Good Loan Applications** | Applications classified as good loans |
| **Bad Loan Applications** | Applications classified as bad loans |
| **Good Loan Funded Amount** | Amount funded for good loans |
| **Bad Loan Funded Amount** | Amount funded for bad loans |

---

# 📈 Dashboard 1 — Summary

The Summary Dashboard focuses on the overall health and performance of the loan portfolio.

### Main Components

- Total Loan Applications
- Total Funded Amount
- Total Amount Received
- Average Interest Rate
- Average DTI
- Good Loan Applications
- Good Loan Funded Amount
- Good Loan Total Received
- Bad Loan Applications
- Bad Loan Funded Amount
- Bad Loan Total Received
- Loan Status Analysis
- Applications by Loan Status
- Funded Amount by Loan Status
- Amount Received by Loan Status
- Interest Rate by Loan Status
- DTI by Loan Status

### Loan Quality Analysis

Loans are categorized into:

**Good Loans**
- Fully Paid
- Current

**Bad Loans**
- Charged Off

This allows the dashboard to provide a quick view of loan portfolio quality.

---

# 📊 Dashboard 2 — Overview

The Overview Dashboard provides deeper analysis of loan applications.

### Visualizations Included

#### 📅 Monthly Loan Applications
Shows how the number of loan applications changes throughout the year.

#### 🗺️ State-wise Loan Applications
Displays loan application distribution across different U.S. states.

#### 💳 Loan Term Analysis
Compares loan applications across different loan terms:

- 36 Months
- 60 Months

#### 👨‍💼 Employment Length
Analyzes loan applications based on the borrower's employment experience.

#### 🎯 Loan Purpose
Shows the number of applications for different purposes such as:

- Debt Consolidation
- Credit Card
- Home Improvement
- Major Purchase
- Small Business
- Car
- Wedding
- Medical
- Moving
- House
- Vacation
- Education
- Renewable Energy

#### 🏠 Home Ownership
Analyzes applications based on home ownership categories such as:

- Rent
- Mortgage
- Own

---

# 🔍 Interactive Filters

The dashboard contains interactive slicers that allow users to filter the analysis dynamically.

### Available Filters

- **Loan Grade**
  - A
  - B
  - C
  - D
  - E
  - F
  - G

- **Loan Purpose**
  - Car
  - Credit Card
  - Debt Consolidation
  - Educational
  - Home Improvement
  - And more

These filters allow users to perform focused analysis on specific loan segments.

---

# 🧮 Excel Techniques Used

The project demonstrates several important Excel data analytics techniques.

### Data Preparation

- Data cleaning
- Handling missing values
- Data type validation
- Date formatting
- Duplicate checking
- Data validation

### Data Analysis

- Pivot Tables
- Pivot Charts
- Excel formulas
- Aggregations
- Conditional calculations
- Percentage calculations
- Month-over-Month analysis
- KPI calculations

### Dashboard Development

- Slicers
- Interactive filters
- KPI cards
- Doughnut charts
- Bar charts
- Line charts
- Treemap
- Map visualization
- Conditional formatting
- Dashboard navigation

---

# 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Microsoft Excel** | Data cleaning, analysis and dashboard development |
| **Pivot Tables** | Data aggregation and analysis |
| **Pivot Charts** | Interactive visualizations |
| **Excel Slicers** | Interactive filtering |
| **Excel Formulas** | KPI and business metric calculations |

---

# 📂 Project Structure

```text
Finance domain Analysis/
│
├── 📊 Dashboard File
│
├── 📁 dashboard-imgs/
│   ├── overview.png
│   └── summary.png
│
└── README.md
