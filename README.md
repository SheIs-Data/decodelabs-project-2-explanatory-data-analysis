# 📊 DecodeLabs Project 2 — Exploratory Data Analysis

> Turning raw e-commerce data into meaningful business insights using Microsoft Excel.

---

## 📌 Project Overview

This project is part of my **DecodeLabs Data Analytics Internship**, where I applied exploratory data analysis techniques to an e-commerce dataset.

The objective was to move beyond simply cleaning data and use analytical techniques to uncover:

- Trends in order activity
- Sales performance over time
- Product performance
- Order status patterns
- Customer payment preferences
- Unusual and high-value transactions
- Actionable business insights

The entire analysis was completed using **Microsoft Excel**.

---

## 🎯 Project Objectives

The analysis focused on:

1. Understanding the structure and characteristics of the dataset
2. Calculating descriptive statistics
3. Identifying trends over time
4. Investigating potential outliers
5. Creating meaningful visualizations
6. Translating analytical findings into business insights

---

## 🛠️ Tools Used

- Microsoft Excel
- PivotTables
- PivotCharts
- Excel formulas
- Descriptive statistics
- IQR outlier analysis
- Box & Whisker charts

---

## 🔎 Analysis Performed

### 1. Descriptive Statistics

Key statistics were calculated to understand the distribution and
range of important numerical variables.

### 2. Trend Analysis

Monthly order activity and sales performance were analyzed to
identify changes in customer activity and revenue generation.

### 3. Product Performance

Products were compared based on total sales to identify the
strongest contributors to revenue.

### 4. Order Status Analysis

Orders were analyzed across different statuses including:

- Cancelled
- Delivered
- Pending
- Returned
- Shipped

### 5. Payment Method Analysis

Payment methods were compared to understand customer payment
preferences.

### 6. Outlier Analysis

The IQR method was used to identify unusually high TotalPrice
values.

Eight potential outliers were identified, ranging from
**3,334.00 to 3,456.40**.

Further investigation showed that these orders had a quantity of
5 and relatively high unit prices. They were therefore retained
rather than removed as data errors.

---

## 📈 Key Findings

### Orders Over Time

June recorded the highest order volume with **147 orders**, while
September recorded the lowest with **73 orders**.

### Sales Performance

January recorded total sales of **124,313.23**, while February
recorded **112,344.78**.

### Order Status

Cancelled orders represented the largest status category with
**250 orders**, while delivered orders accounted for **231 orders**.

### Outliers

Eight potential high-value TotalPrice outliers were identified
using the IQR method.

The analysis suggested that these observations were associated
with high quantities and unit prices rather than obvious data-entry
errors.

---

## 📊 Visualizations

The project includes visualizations covering:

- Orders Over Time
- Total Sales Over Time
- Top Products by Sales
- Order Status Distribution
- Payment Method Distribution
- TotalPrice Distribution and Outliers

---

## 💡 Business Value

This analysis demonstrates how exploratory data analysis can help
businesses understand customer activity, sales performance,
product contribution, order behavior, and unusual transactions.

The findings can support better decisions around product
performance, order management, customer behavior, and sales
monitoring.

---

## 📁 Repository Structure

```text
├── data/
│ └── cleaned/
│
├── project/
│   └── DecodeLabs_Project_2_EDA.xlsx
│
├── visuals/
│
├── documentation/
│   ├── Data_Dictionary.md
│   └── Methodology.md
│
└── README.md
