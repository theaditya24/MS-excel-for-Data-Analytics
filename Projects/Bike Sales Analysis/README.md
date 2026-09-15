# 🚲 Bike Sales Analysis — Microsoft Excel

![Microsoft Excel](https://img.shields.io/badge/Microsoft%20Excel-Data%20Analysis-217346?style=for-the-badge\&logo=microsoftexcel\&logoColor=white)
![Data Analytics](https://img.shields.io/badge/Data%20Analytics-Project-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Project%20Status-Completed-success?style=for-the-badge)

> **An end-to-end Microsoft Excel data analytics project focused on understanding customer demographics, income, commuting behavior, and the factors influencing bicycle purchases.**

---

## 📌 Project Overview

The **Bike Sales Analysis** project is an end-to-end data analytics project developed using **Microsoft Excel**.

The objective of this project is to analyze customer demographic and behavioral data to identify patterns associated with **bike purchasing decisions**.

The analysis transforms raw customer data into meaningful business insights using:

* Data cleaning and transformation
* Feature engineering
* Pivot Tables
* Aggregation and segmentation
* Data visualization
* Interactive dashboarding
* Business-oriented interpretation

The final output is an **Excel-based analytical dashboard** that allows users to understand customer purchasing behavior across different demographic and behavioral segments.


### 📊 Dashboard Preview

The final interactive dashboard developed in Microsoft Excel is shown below:

<p align="center">
  <img src="assets/bike%20sales%20dashboard.png" alt="Bike Sales Analysis Dashboard" width="100%">
</p>

> **Dashboard:** An interactive Excel dashboard summarizing bike purchasing behavior across income, gender, commute distance, age groups, marital status, region, and education.

---

## 🎯 Business Problem

A bicycle retailer wants to better understand its customers and determine which customer characteristics are associated with purchasing a bike.

The business needs answers to questions such as:

* Which customer segments are more likely to purchase a bike?
* Does income influence bike purchasing behavior?
* Does gender affect purchasing patterns?
* How does commuting distance relate to bike purchases?
* Which age groups are more likely to purchase bikes?
* Which customer segments should the business target with marketing campaigns?
* How can customer characteristics be used to improve sales strategies?

This project uses Excel-based analytics to answer these questions and convert the raw dataset into actionable business insights.

---

# 📊 Dataset

The dataset contains **1,000 customer records** used for the analysis.

The original dataset is available in the Excel workbook under the:

`bike_buyers`

worksheet.

### Dataset Attributes

| Column             | Description                           |
| ------------------ | ------------------------------------- |
| `ID`               | Unique customer identifier            |
| `Marital Status`   | Customer's marital status             |
| `Gender`           | Customer gender                       |
| `Income`           | Annual customer income                |
| `Children`         | Number of children                    |
| `Education`        | Customer education level              |
| `Occupation`       | Customer occupation                   |
| `Home Owner`       | Whether the customer owns a home      |
| `Cars`             | Number of cars owned                  |
| `Commute Distance` | Customer's commuting distance         |
| `Region`           | Customer's geographical region        |
| `Age`              | Customer age                          |
| `Purchased Bike`   | Whether the customer purchased a bike |

---

# 🗂️ Project Structure

The Excel workbook is organized into multiple worksheets:

```text
Bike Sales Analysis
│
├── bike_buyers
│   └── Original/raw customer dataset
│
├── Working Sheet
│   └── Cleaned and transformed dataset
│
├── Pivot Tables
│   └── Analytical summaries and aggregations
│
└── Dashboard
    └── Final visual dashboard
```

---

# 🔄 Data Analysis Workflow

The project follows a structured analytics workflow:

```text
Raw Data
   ↓
Data Cleaning
   ↓
Data Transformation
   ↓
Feature Engineering
   ↓
Pivot Table Analysis
   ↓
Data Visualization
   ↓
Dashboard Development
   ↓
Business Insights
```

---

# 🧹 1. Data Cleaning & Preparation

The raw dataset was first reviewed and prepared for analysis.

Key preparation activities included:

### Data validation

The dataset was checked for:

* Missing values
* Inconsistent categorical values
* Incorrect formatting
* Duplicate or unnecessary records
* Data-type consistency

### Categorical standardization

Some categorical fields were transformed into more readable formats.

For example:

```text
M → Male
F → Female
```

and:

```text
M → Married
S → Single
```

This makes the analysis easier to understand for business users.

---

# 🛠️ 2. Feature Engineering

A new analytical feature called:

### `Age Brackets`

was created to segment customers into meaningful age groups.

The categories used were:

| Age Bracket | Definition |
| ----------- | ---------- |
| Adolescent  | Age < 31   |
| Middle Age  | 31–55      |
| Old Age     | > 55       |

This segmentation makes it easier to compare bike-purchasing behavior across different customer life stages.

---

# 📈 3. Pivot Table Analysis

Pivot Tables were used extensively to summarize the dataset and identify relationships between customer attributes and bike purchases.

The analysis includes:

### Income Analysis

Average income was compared between:

* Customers who purchased a bike
* Customers who did not purchase a bike

The analysis was further segmented by gender.

### Commute Distance Analysis

Bike purchases were analyzed across different commuting-distance categories:

* 0–1 Miles
* 1–2 Miles
* 2–5 Miles
* 5–10 Miles
* More than 10 Miles

### Age Group Analysis

Bike purchases were analyzed across:

* Adolescent
* Middle Age
* Old Age

This helps identify which age segment represents the strongest customer base.

---

# 📊 Key Analytical Findings

The analysis produced several important observations.

## 💰 Income & Bike Purchases

The dataset shows that customers who purchased bikes generally have a higher average income than customers who did not.

Overall:

| Purchase Status  | Average Income |
| ---------------- | -------------: |
| Did Not Purchase |       ~$54,875 |
| Purchased        |       ~$57,963 |

This suggests that **income may have a positive relationship with bike purchasing behavior**.

---

## 👨‍👩‍👧 Gender & Income

The analysis also compares average income across gender and purchase status.

### Female Customers

| Purchase Status  | Average Income |
| ---------------- | -------------: |
| Did Not Purchase |       ~$53,440 |
| Purchased        |       ~$55,774 |

### Male Customers

| Purchase Status  | Average Income |
| ---------------- | -------------: |
| Did Not Purchase |       ~$56,208 |
| Purchased        |       ~$60,124 |

Male customers in the dataset show a higher average income in both purchase categories.

---

# 🚗 Commute Distance & Bike Purchases

Commute distance is one of the most interesting variables in the analysis.

| Commute Distance | No Purchase | Purchase | Total |
| ---------------- | ----------: | -------: | ----: |
| 0–1 Miles        |         166 |      200 |   366 |
| 1–2 Miles        |          92 |       77 |   169 |
| 2–5 Miles        |          67 |       95 |   162 |
| 5–10 Miles       |         116 |       76 |   192 |
| >10 Miles        |          78 |       33 |   111 |

### Key observation

Customers commuting **0–1 miles** represent the largest customer segment and also have a high number of bike purchases.

Customers commuting **more than 10 miles** have considerably fewer bike purchases.

This indicates that commuting distance may be an important factor when evaluating potential bike customers.

---

# 👥 Age Group & Bike Purchases

Bike purchases were also analyzed across different age groups.

| Age Group          | No Purchase | Purchase | Total |
| ------------------ | ----------: | -------: | ----: |
| Middle Age (31–55) |         331 |      388 |   719 |
| Old Age (>55)      |         117 |       54 |   171 |
| Adolescent (<31)   |          71 |       39 |   110 |

### Key observation

The **Middle Age (31–55)** segment is the dominant customer group in the dataset.

It also has the highest number of bike purchases.

This makes the middle-aged customer segment particularly important for targeted marketing and sales strategies.

---

# 📊 Dashboard

The final stage of the project is an interactive **Bike Sales Dashboard** developed in Microsoft Excel.

The dashboard brings together the major findings of the analysis in a visual and business-friendly format.

### Dashboard objectives

The dashboard is designed to help users quickly understand:

* Customer demographics
* Bike purchase distribution
* Income patterns
* Age-group behavior
* Commute-distance behavior
* Customer segmentation
* Overall purchasing trends

### Dashboard Components

The dashboard uses Excel visualization and analytical components such as:

* Charts
* Pivot Tables
* Slicers/filters
* KPI-style summaries
* Customer segmentation
* Interactive visual analysis

The goal is to provide a **single-page decision-support view** instead of requiring users to manually analyze raw data.

---

# 🧰 Tools & Technologies

| Tool                   | Purpose                                                   |
| ---------------------- | --------------------------------------------------------- |
| **Microsoft Excel**    | Data cleaning, transformation, analysis and visualization |
| **Excel Pivot Tables** | Data aggregation and segmentation                         |
| **Excel Charts**       | Data visualization                                        |
| **Excel Slicers**      | Interactive filtering                                     |
| **Excel Formulas**     | Feature engineering and calculations                      |
| **GitHub**             | Project version control and portfolio presentation        |

---

# 🧠 Excel Skills Demonstrated

This project demonstrates practical knowledge of Microsoft Excel for data analytics, including:

### Data Preparation

* Data cleaning
* Data validation
* Data standardization
* Data formatting

### Data Transformation

* Creating calculated fields
* Creating age categories
* Categorical mapping
* Feature engineering

### Data Analysis

* Pivot Tables
* Aggregation
* Grouping
* Segmentation
* Comparative analysis

### Data Visualization

* Charts
* Dashboard design
* Interactive filtering
* KPI presentation

### Business Analytics

* Customer segmentation
* Trend identification
* Behavioral analysis
* Insight generation
* Business recommendations

---

# 💡 Business Insights

Based on the analysis, several actionable insights can be derived.

### 1. Focus on Middle-Aged Customers

The **31–55 age group** represents the largest portion of the dataset and accounts for the highest number of bike purchases.

**Recommendation:**

Target this segment with dedicated marketing campaigns and product offerings.

---

### 2. Target Short-Distance Commuters

Customers commuting **0–1 miles** show strong bike purchasing activity.

**Recommendation:**

Position bicycles as a convenient and economical transportation option for short-distance commuters.

---

### 3. Consider Income in Customer Targeting

Customers who purchased bikes have a higher average income than non-buyers.

**Recommendation:**

Consider income as one of the segmentation variables when designing targeted campaigns or premium product offerings.

---

### 4. Use Customer Segmentation

Combining:

* Age
* Gender
* Income
* Commute distance
* Occupation
* Education

can help create more precise customer segments.

This can improve:

* Marketing effectiveness
* Customer targeting
* Product positioning
* Sales conversion

---

# 🎯 Potential Business Applications

The analysis can support several business decisions, including:

### Marketing

Identify customer segments with higher purchase likelihood.

### Sales

Prioritize high-potential customer groups.

### Product Strategy

Understand which customers may be more interested in bicycle products.

### Customer Segmentation

Develop targeted campaigns based on demographic and behavioral characteristics.

### Business Intelligence

Use the dashboard as a recurring reporting tool for management decision-making.

---

# ⚠️ Limitations

Although the analysis provides useful insights, there are several limitations.

* The dataset contains only 1,000 customer records.
* The analysis is based on historical customer information.
* Correlation between variables does not necessarily imply causation.
* The dataset does not provide detailed information about product type or bike category.
* Marketing exposure and customer preferences are not included.
* Purchase amount/revenue information is not available.

Therefore, the results should be interpreted as **descriptive insights rather than causal conclusions**.

---

# 🚀 Future Improvements

The project can be further enhanced by adding:

* Customer Lifetime Value analysis
* Revenue and profit analysis
* Product-level analysis
* Regional sales analysis
* Advanced customer segmentation
* Purchase probability modeling
* Statistical correlation analysis
* Regression analysis
* Power BI dashboard integration
* Automated Excel reporting
* Predictive modeling for bike purchase likelihood

---

# 📁 Repository

This project is part of my **Microsoft Excel for Data Analytics** project portfolio.

Repository:

**MS Excel for Data Analytics**

Project:

**Bike Sales Analysis**

---

# 👨‍💻 Author

**Aditya Raj**

Aspiring Data Analyst passionate about transforming raw data into meaningful business insights using:

* Microsoft Excel
* SQL
* Python
* Data Visualization
* Business Analytics

---

# ⭐ Project Highlights

```text
✔ 1,000 customer records analyzed
✔ Data cleaning and transformation
✔ Feature engineering
✔ Age segmentation
✔ Income analysis
✔ Gender-based analysis
✔ Commute-distance analysis
✔ Bike purchase analysis
✔ Pivot Table analysis
✔ Interactive Excel Dashboard
✔ Business insights and recommendations
```

---

# 📌 Conclusion

The **Bike Sales Analysis** project demonstrates how Microsoft Excel can be used as a complete data analytics tool — from raw data preparation to business intelligence and dashboard development.

By combining **data cleaning, feature engineering, Pivot Tables, visualization, and customer segmentation**, the project transforms raw customer information into actionable insights.

The analysis highlights the importance of **age, income, gender, and commute distance** when understanding bike purchasing behavior and demonstrates how Excel can support practical, data-driven business decisions.

---

## 📜 License

This project is intended for **educational and portfolio purposes**.
