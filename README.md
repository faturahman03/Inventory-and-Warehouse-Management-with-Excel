# 📦 Inventory & Warehouse Management Dashboard (Excel-Based)

## 🧭 Executive Summary
This project focuses on analyzing and visualizing **Inventory & Warehouse Management** data using **Microsoft Excel** as the primary tool.  
The dataset, sourced from **Kaggle (open source)**, contains detailed records of products, suppliers, warehouse locations, stock levels, pricing, and turnover rates.  

The main objective is to provide **clear and actionable insights** regarding inventory performance — such as identifying stock inefficiencies, turnover trends, and product status distribution — to support better operational decision-making and stock optimization.

Through the development of an **interactive Excel dashboard** (utilizing Pivot Tables and Power Pivot), the analysis delivers both **quantitative summaries** and **visual insights**, enabling stakeholders to quickly monitor inventory health, assess stock risks, and prioritize replenishment activities.

---

## 💼 Business Problem
Effective inventory management is crucial for maintaining operational efficiency, ensuring product availability, and minimizing holding costs.  
However, organizations often face challenges such as:
- Overstock situations that lead to high storage costs or product waste.
- Stockout issues that disrupt sales and customer satisfaction.
- Slow-moving inventory that ties up working capital.
- Inconsistent stock levels across multiple warehouses.

This project aims to address these common problems by analyzing key performance indicators (KPIs) and creating a data-driven dashboard that highlights:
- **Total and average stock performance.**
- **Inventory turnover efficiency.**
- **Product expiration risk.**
- **Stock distribution across product categories and warehouses.**
- **Overall product status and availability.**

By turning raw data into actionable insights, this analysis helps business teams make informed decisions on **reorder planning, warehouse utilization, and inventory optimization**.

---

## ⚙️ Methodology
All data processing, cleaning, transformation, and visualization were conducted entirely using **Microsoft Excel** (including Power Query, Pivot Table, and Power Pivot).  
The workflow includes the following key steps:

### 🧹 Data Cleaning & Transformation
- **Removed duplicates** based on `Product_ID` to ensure data integrity.  
- **Handled missing values**, where only one row contained null data, and addressed accordingly.  
- **Validated and corrected inconsistencies**, ensuring accuracy across numerical and categorical fields.  
- **Standardized data formats**, especially date columns, using **Power Query** for consistent time-based calculations.  
- **Created two new calculated fields:**
  - `expired_status` → derived from `Last_Order_Date` and `Expiration_Date`, indicating whether a product is expired or still active.  
  - `total_stock` → calculated as the sum of `Stock_Quantity` and `Reorder_Quantity`, representing the complete stock count per item.

### 📊 Data Analysis & Visualization
Using **Pivot Table** and **Power Pivot**, the following metrics and visual dashboards were developed:
- **Summary Section:**
  - Total stock  
  - Average turnover rate  
  - Total expired products
- **Stock per Category:**  
  Bar chart showing total stock by product category.
- **Re-stock Needed:**  
  Identification of warehouses with the lowest stock levels (including *Bottom 10 Warehouses* insight).
- **Inventory Turnover:**  
  Listing of products with the lowest turnover rate and corresponding stock quantities.
- **Product Status Overview:**  
  Distribution of product status (Active, Discontinued, Backordered) and their percentage of total products.

These visual components are designed to provide **a holistic view of warehouse performance** and allow stakeholders to quickly identify critical areas requiring attention.

---

## 🧠 Skills & Tools Utilized

### 🧩 Excel Analytical Skills
- **Data Aggregation** — summarizing large datasets efficiently using Pivot Tables and calculated measures.  
- **VLOOKUP & Lookup Functions** — for merging reference data and ensuring relational integrity.  
- **Pivot Table / Power Pivot Modeling** — building data models, defining relationships, and calculating KPIs dynamically.  
- **Power Query** — for data cleaning, transformation, and standardization of formats (especially dates).  
- **Dashboard Design** — developing interactive and insightful visualizations for operational reporting.

### 🛠️ Technical Environment
- Microsoft Excel (Power Query, Power Pivot, Pivot Chart)  
- Kaggle (as data source)  
- GitHub (for project documentation and versioning)

---

## 📈 Results and Business Recommendations
*(To be completed — include insights such as overstock vs stockout findings, turnover trends, and key recommendations for inventory optimization.)*

---

## 🚀 Next Steps
*(To be added later — potential improvements, such as predictive restocking, automation, or integration with supplier data.)*

---

## 📂 Repository Structure
