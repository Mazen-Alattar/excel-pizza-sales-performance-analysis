# 🍕 Pizza Sales & Orders Performance Dashboard (Excel)
<img src="https://raw.githubusercontent.com/Mazen-Alattar/excel-pizza-sales-performance-analysis/refs/heads/main/excel-pizza-sales-performance-analysis/images/dashboard_preview.png" width="900">

## 📌 Project Overview
This project analyzes pizza sales and orders performance data to uncover sales trends, customer ordering behavior, and product performance.
The analysis was built using **Microsoft Excel** with a strong focus on **Power Query** for data transformation and **creative dashboard design**.

The dataset was sourced from **Kaggle**, and the project highlights both analytical thinking and innovative visualization techniques.

---

## 🗂 Dataset Information
- **Source:** Kaggle
- **Domain:** Sales & Orders
- **Data Type:** Transactional sales data

### Original Columns
- Pizza ID  
- Quantity Sold  
- Order Date  
- Order Time  
- Unit Price  
- Pizza Size  
- Pizza Category  
- Pizza Name  

---

## 🔄 Data Preparation (Power Query)

All data preparation and feature engineering were performed using **Power Query**.

### Data Cleaning
- Ensured correct data types for date, time, and numeric fields
- Standardized column names
- Removed inconsistencies in categorical columns

### Derived Columns

The following new columns were created to support analysis:

- **Revenue**  
  Revenue = Quantity Sold × Unit Price
- **Hour** (extracted from Order Time)
- **Year** (extracted from Order Date)
- **Month** (extracted from Order Date)
- **Day** (extracted from Order Date)

These transformations enabled time-based, category-based, and performance-driven analysis.

---

### Dashboard Highlights
- Fully interactive dashboard using **Slicers** (Month & Year)
- KPI cards showing:
- Total Revenue
- Total Pizza Sold
- Total Orders
- Average Orders per Transaction
- Combination of **standard and custom-designed charts**
- Focus on clear storytelling and visual clarity

---

## 📈 Analysis & Key Insights

### Sales Performance
- Total revenue exceeds **$800K**, driven by a high volume of orders.
- Sales show clear variation across months and days of the week.
- Certain days consistently record higher quantities sold.

### Product Insights
- **Large and Extra-Large** pizza sizes are the most ordered.
- **Classic and Chicken** categories generate the highest revenue.
- A small number of pizza types account for a large share of total revenue.

### Customer Ordering Behavior
- Order volume peaks during specific hours of the day.
- Monthly trends highlight seasonality in customer demand.

---

## 🎨 Visualization & Chart Innovation
One of the key strengths of this project is the use of **non-traditional and creatively designed charts**, including:
- Funnel-style category comparisons
- Custom donut charts for size and category distribution
- Horizontal ranking visuals for top pizzas and revenue contribution
- Clean KPI cards with icons to improve dashboard readability

These visual choices enhance insight discovery and make the dashboard more engaging and intuitive.

---

## 🛠 Tools & Technologies
- **Microsoft Excel**
- Power Query (Data cleaning & transformation)
- Pivot Tables
- Custom Charts & Visual Design
- Interactive Slicers

---

## 🎯 Project Goal
This project was created as part of a data analytics portfolio to demonstrate:
- Strong Excel and Power Query skills
- Analytical thinking using real-world sales data
- Creative dashboard design and data storytelling  

Targeted toward **Data Analyst Internship** opportunities.

