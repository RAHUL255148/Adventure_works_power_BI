# Adventure Works Power BI Analysis (PQ1)

A comprehensive Power BI report built using the Adventure Works dataset, showcasing end-to-end data import, modeling, DAX computations, and interactive dashboarding.

---

## 📁 Project Overview

This project demonstrates the typical Power BI workflow, covering:

1. **Data Import & Transformation**  
   - Load source tables (e.g., Sales, Returns, Customers, Products, Calendar, Territory)  
   - Clean and shape data in Power Query: fix data types, remove nulls, rename columns, create calculated columns

2. **Data Modeling**  
   - Establish relationships between fact and dimension tables  
   - Implement star schema: Fact tables (`Sales`, `Returns`) linked to dimensions (`Customers`, `Products`, `Calendar`, `Territory`)  
   - Configure cardinality and cross-filter directions appropriately

3. **DAX Measures & Calculations**  
   - KPIs: Revenue, Cost, Profit, Orders, Returns  
   - Time intelligence: YTD metrics, Month-over-Month, Rolling Averages  
   - Advanced DAX using `CALCULATE`, `SUMX`, `DATESYTD`, `DATEADD`, etc.

4. **Dashboards & Visualizations**  
   - Executive Summary: Revenue, Orders, Profit KPIs, trend charts  
   - Geo Analysis: Sales by region/country/continent  
   - Product Insights: Top products, performance trends, return analysis  
   - Customer Analysis: Top customers, demographic insights, segmentation

---


