# E-commerce Sales Dashboard

### This project analyzes and visualizes online retail sales data to provide business insights through interactive dashboards. It is built using Python for data processing and exploration and Tableau for dashbaords.
---

## Dataset

**Source**: [UCI Machine Learning Repository – Online Retail Data Set](https://archive.ics.uci.edu/ml/datasets/online+retail)  

This dataset contains transactional data for a UK-based online retailer from **Dec 1, 2010 to Dec 9, 2011**, including sales across multiple countries.

---

## Data Cleaning Steps

- Removed rows with missing `CustomerID`
- Removed transactions with negative quantities (i.e., returns)
- Created `TotalPrice = Quantity × UnitPrice`
- Extracted `Year`, `Month`, `Weekday`, and `Hour` from `InvoiceDate`

---

## Exploratory Data Analysis

Key business questions answered:

- What is the monthly revenue trend?
- Which products generate the most revenue?
- What are the top countries by total sales?
- What time of day do customers tend to order the most?
- Who are the most valuable customers?

---

## Key Metrics & Visualizations

- **Total Revenue, Orders, Customers (KPIs)**
- **Revenue Over Time** – Line chart
- **Top 10 Products** – Bar chart
- **Sales by Country** – Geo map or bar plot
- **Order Hour vs. Weekday** – Heatmap
- **Top Customers** – Customer lifetime value chart

---

## Tools & Libraries Used

- `pandas` – data manipulation
- `matplotlib`, `seaborn`, `plotly` – data visualization
- `jupyter notebook` – project development
- `Tableau` – dashboards

---
