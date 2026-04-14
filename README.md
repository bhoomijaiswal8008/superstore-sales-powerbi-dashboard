# 📊 Superstore Sales Dashboard | Power BI Project

## 📌 Project Overview
The **Superstore Sales Dashboard** is an interactive Power BI project designed to analyze retail sales performance and extract meaningful business insights. The dashboard enables users to explore sales trends, identify top-performing products and regions, and make data-driven decisions through dynamic visualizations and KPIs.

## 🎯 Objectives
- Analyze overall sales performance of the Superstore dataset.
- Identify top-performing products, cities, and regions.
- Monitor key business metrics such as revenue and profit.
- Provide an interactive and user-friendly dashboard for stakeholders.

## 📂 Dataset
The project uses the popular **Superstore Sales Dataset**, which includes information such as:
- Order Date
- Ship Mode
- Customer Details
- Product Category & Sub-Category
- Sales, Quantity, and Profit
- City, State, and Region

## 🛠️ Tools & Technologies
- **Power BI** – Dashboard creation and visualization
- **Power Query** – Data cleaning and transformation
- **DAX (Data Analysis Expressions)** – KPI and measure calculations
- **Data Modeling** – Establishing relationships between tables

## 📊 Dashboard Features
### 🔹 Interactive Filters
- Slicers for **Year**, **Month**, and **Day** to dynamically explore sales trends.

### 🔹 Sales Analysis
- Sales by **Category** and **Sub-Category**
- **Top 10 Products** by Quantity Sold
- **Top 10 Cities** based on Sales Quantity
- Sales distribution by **Region** and **Ship Mode**

### 🔹 Key Performance Indicators (KPIs)
- **Total Revenue**
- **Total Profit**
- **Total Quantity**
- **Profit Percentage**

## 🧮 DAX Measures (Sample)

```DAX
Total Revenue = SUM(Superstore[Sales])

Total Profit = SUM(Superstore[Profit])

Total Quantity = SUM(Superstore[Quantity])

Profit Percentage = 
DIVIDE([Total Profit], [Total Revenue], 0) * 100
