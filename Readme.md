# 📊 E-Commerce Sales Analysis Dashboard – Power BI

This project is an **end-to-end Power BI Dashboard** built to analyze and visualize the sales performance of an E-Commerce store.  
It provides insights into total sales, profit, customer behavior, category performance, and city-wise sales distribution.

---

## 🚀 Project Overview
The goal of this dashboard is to help businesses track key KPIs, identify trends, and make data-driven decisions.  
The report includes multiple visuals representing sales by category, sub-category, customer, city, and payment modes.

---

## 🛠️ Tools & Technologies
- **Power BI Desktop**
- **Power Query (ETL)**
- **DAX (Data Analysis Expressions)**
- **Excel / CSV (raw data source)**

---

## 📈 Key Insights Provided
### ✔️ **KPI Metrics**
- **Total Sales**
- **Total Profit**
- **Total Quantity Sold**

### ✔️ **Category & Sub-Category Analysis**
- Sales by Category (Pie Chart)
- Sales by Sub-Category by Profit (Combo Chart)

### ✔️ **Customer Insights**
- Top 5 Customers by Total Sales

### ✔️ **Geographic Insights**
- Top 5 Cities by Total Sales

### ✔️ **Payment Mode Breakdown**
- UPI  
- COD  
- Credit Card  
- Debit Card  

---

## 🧹 Data Cleaning & Preparation
Performed using **Power Query**:
- Removed null/duplicate values  
- Standardized column names  
- Extracted date fields (Year, Quarter, Month)  
- Created a Date Table  
- Ensured proper data types  

---

## 🧮 DAX Measures Used
Some of the important DAX measures created:
```DAX
Total Sales = SUM(Sales[Sales Amount])

Total Profit = SUM(Sales[Profit])

Total Quantity = SUM(Sales[Quantity])

Dash Board Preview
<img width="1536" height="1024" alt="dashboard image" src="https://github.com/user-attachments/assets/3139b6b9-5ef0-4972-86dd-e45f517a298d" />
