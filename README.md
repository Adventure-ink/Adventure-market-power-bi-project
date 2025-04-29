# 📊 Adventure Market Sales Dashboard

## 👨‍💻 Project by: Shivam Rana  
**Type:** Portfolio Project | **Tool:** Microsoft Power BI

---

## 🧩 Project Objective

The purpose of this Power BI project is to create an interactive dashboard for a fictional retail company called **Adventure Market**. The goal is to analyze sales data across regions, products, and time to uncover trends and provide actionable business insights. This project simulates a real-world business intelligence use case to demonstrate skills in data visualization, analysis, and dashboard design.

---

## 📁 Dataset Overview

- **Source:** Sample AdventureWorks dataset (cleaned version)
- **Size:** ~10,000 rows
- **Key Columns:**
  - `Order Date`, `Product Category`, `Sales`, `Profit`, `Quantity`, `Customer`, `Region`
- **Data Cleaning:**
  - Removed null values
  - Created a `Year-Month` column for trend analysis
  - Calculated measures for total sales, total profit, and profit margin

---

## 🛠️ Tools & Techniques Used

- **Power BI Desktop**
- **Power Query** for data transformation
- **DAX** for calculated measures:
  ```DAX
  Total Sales = SUM(Sales)  
  Total Profit = SUM(Sales) - Sum(Costs)  
  Profit Margin = DIVIDE(Total Profit, Total Sales)
  ```
- **Visualizations:**
  - Line Charts, Bar Charts,Stacked Bar Charts,Tables
  - Slicers and Filters for interactivity
  - Drill-through pages for product-level insights

---

## 📈 Key Visuals & Insights

### 🔹 Sales Trend by Month (Line Chart)
- Sales show a steady increase over time most of it in Q4.

### 🔹 Sales by Region 
- The North-West region leads in both revenue and profitability.

### 🔹 Product Breakdown (Stacked Bar Chart)
- Top 5 products are Hermanos, Tell tale, Ebony, Tri-State, High Top

### 🔹 Customer Segments (Stacked Bar Chart)
- Bronze card Consumers drive most of the sales and Revenue While Silver card drive least revenue, .

### 🔹 Top Products by Profit (Table)
- Shows best-performing products using conditional formatting to highlight profitability.

---

## 📌 Summary of Insights

- **Top-Performing Region:** North-West  
- **Most Profitable Product:** Hermanos  
- **Sales Strategy:** Focus on high-margin products and bronze members   
- **Time-Based Insight:** Q4 is peak season; ideal for promotional campaigns
- **Most Return Product:** Hermanos with total of 274 products

---

## ✅ Conclusion

This dashboard enables decision-makers at Adventure Market to:
- Monitor key performance indicators (KPIs)
- Identify sales trends across time and geography
- Make strategic decisions based on real-time data

This project demonstrates my ability to build professional Power BI dashboards, clean and transform raw data, and deliver business-focused insights using data visualization.

---

## 📷 Dashboard Preview

![Screenshot 2025-04-29 215921](https://github.com/user-attachments/assets/e80379e0-646f-4880-9864-aaf261818476)


---

## 🔗 Live Demo or PBIX File

> Upload the `.pbix` file to your GitHub repo and link it here:

[📁 Download Dashboard PBIX](./adventure_market.pbix)
