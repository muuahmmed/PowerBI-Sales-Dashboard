# 📊 Sales Performance Analytics - Wide World Importers

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Data_Analysis_Expressions-0078D4?style=for-the-badge)
![Data Modeling](https://img.shields.io/badge/Data_Modeling-Star_Schema-green?style=for-the-badge)

## 🌟 Overview
How can a business transform raw sales rows into actionable strategic decisions? This project is an end-to-end Power BI solution that analyzes the performance of **Wide World Importers**. 

I didn't just build charts; I built a **Decision-Support System**. Using advanced DAX, robust data modeling, and UI/UX principles, this dashboard uncovers hidden trends in sales, profit margins, and employee performance.

---

## 🖼️ Dashboard Preview
*Visualizing the pulse of the business*

<p align="center">
  <img src="screenshots/Screenshot 2026-01-20 022155.png" width="48%" />
  <img src="screenshots/Screenshot 2026-01-20 022215.png" width="48%" />
</p>
<p align="center">
  <img src="screenshots/Screenshot 2026-01-20 022229.png" width="90%" />
</p>

---

## 🚀 Key Insights & Features
* **Dynamic Sales Tracking:** Real-time visibility into Total Sales, Profit, and Quantity.
* **Geospatial Analysis:** Mapping sales across different territories to identify high-growth regions.
* **Product Performance:** Identifying "Star" products vs "Underperformers" using Profit Margin analysis.
* **Salesperson Leaderboard:** Tracking individual employee impact on the bottom line.
* **Time Intelligence:** Year-over-Year (YoY) and Month-over-Month (MoM) comparisons to detect seasonality.

---

## 🛠️ The Technical Workflow

### 1. Data Transformation (Power Query)
* Cleaned and structured raw CSV files (FactSale, DimCity, DimCustomer, etc.).
* Handled missing values and optimized data types for performance.
* Created a dedicated **Calendar Table** for advanced time-intelligence.

### 2. Data Modeling
Implemented a **Star Schema** to ensure high performance and scalability:
* **Fact Table:** `FactSale`
* **Dimension Tables:** `DimCustomer`, `DimCity`, `DimEmployee`, `DimStockItem`, and `DimDate`.
* **Relationship:** One-to-Many relationships established to maintain data integrity.

### 3. DAX Calculations
Some of the key measures created:
* **Total Profit:** `SUM(FactSale[Profit])`
* **Profit Margin %:** `DIVIDE([Total Profit], [Total Sales], 0)`
* **Growth Metrics:** Using `CALCULATE` and `SAMEPERIODLASTYEAR` for trend analysis.

---

## 🎓 Acknowledgement
This project was inspired by the **Data Analysis Pro** curriculum by **Ahmed Abdel Baset**. It was a deep dive into:
* Advanced DAX optimization.
* Data storytelling and effective visualization.
* Business-centric dashboard design.

---

## 📬 Connect with Me
If you have any feedback or want to discuss Data Analytics, feel free to reach out!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohammed-magdy-b8a37a1a8/)

---
*Created by Mohammed Magdy*
