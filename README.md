# 👟 Adidas MENA Interactive Sales Dashboard

An interactive Excel dashboard designed to analyze sales performance, profitability, product distributions, customer age demographics, and regional impacts across various categories.

---

## 🚀 Project Overview

This project provides an end-to-end retail performance analysis for Adidas MENA, transforming multi-year transaction logs into dynamic, executive-ready insights. The dashboard tracks core business KPIs—including units sold, revenue trajectory, and profit margins—across 3 main product categories and 5 key regional markets (**Egypt, Iraq, KSA, Lebanon, and Oman**).

<img width="767" height="522" alt="image" src="https://github.com/user-attachments/assets/ccb84597-541b-4f4a-80f7-8882eec5dc9d" />

---

## 📈 Executive Summary KPI Cards

* **Units Sold:** 3,550
* **Total Revenue:** $287,378
* **Profit Margin:** 30%

---

## 🗃️ Dataset Overview

The underlying dataset contains transactional logs covering 2023 through 2025 across the following primary attributes:

* **`Order_ID` & `Order_Date`:** Unique transaction identifiers and timestamps (2023–2025).
* **`SKU` & `Product_Name`:** Specific item designations (*e.g., Ultraboost 22, Copa Sense, Adicolor Hoodie*).
* **`Category`:** Higher-level product classifications (**Footwear**, **Apparel**, **Accessories**).
* **`Region`:** Geographic sales locations (**Egypt, Iraq, KSA, Lebanon, Oman**).
* **`Store_Type`:** Distribution channels (**Online, Retail, Wholesale, Outlet**).
* **`Customer_Age` & `Gender`:** Demographic breakdown parameters (**Male, Female, Other**).
* **`Financial Metrics`:** `Unit_Price`, `Discount` (%), `Revenue`, and net `Profit`.

---

## 💡 Key Visualizations & Analytics Insights

### 1. 💰 Profit Contribution by Product
* **Chart Type:** Bar Chart
* **Key Finding:** Highlighting individual product profits. Top performers include **Ultraboost 22** ($2,685), **Ultraboost Light** ($2,375), **Predator Freak** ($2,340), and **Copa Sense** ($2,288).

### 2. 👥 Demographic Distribution
* **Chart Type:** Pie Chart
* **Key Finding:** Men's products account for the largest share of overall sales (**53.65%**), followed by Female (**45.63%**) and Other (**0.72%**).

### 3. 📦 Category Breakdown (Pareto Rule)
* **Chart Type:** Donut Chart
* **Key Finding:** Footwear and Accessories represent the majority of sales volume:
  * **Footwear:** 64.95%
  * **Accessories:** 25.19%
  * **Apparel:** 9.86%

### 4. 🎂 Age Dynamics on Quantity & Product Category
* **Chart Type:** Multi-category Line Chart
* **Key Finding:** Details purchasing volume trends across customer age groups segmented by category (Accessories, Apparel, Footwear).

### 5. 📅 Revenue & Sales Volume Trends (2023–2025)
* **Chart Type:** Dual-Axis Combo Chart (Columns + Line)
* **Key Finding:** Tracks monthly and yearly fluctuations combining units sold and overall revenue trajectory over three years.

### 6. 🏷️ Discount Impact Analysis
* **Chart Type:** Scatter Plot with Profit Callouts
* **Key Finding:** Demonstrates that higher discount percentages do not necessarily yield higher sales volume or profit margins.

### 7. 🛒 Regional Sales Channel Performance
* **Chart Type:** Pie Chart
* **Key Finding:** Except in Lebanon, online stores generate the highest performance across overall distribution channels:
  * **Online:** 45.51%
  * **Retail:** 35.45%
  * **Wholesale:** 10.54%
  * **Outlet:** 8.50%

### 8. 🗺️ Regional Profit Map
* **Chart Type:** Geospatial Map
* **Key Finding:** Analyzes geographic profit contributions across target regions (Egypt, Iraq, KSA, Lebanon, Oman), with Egypt showcasing top profit contribution.

---

## 📊 Dashboard Key Components & Visuals

### 1. 🎛️ Interactive Slicers & Filters
* **Region Slicer:** Filter metrics by regional markets (**Egypt, Iraq, KSA, Lebanon, Oman**).
* **Gender Slicer:** Segment insights by customer gender (**Female, Male, Other**).
* **Category Slicer:** Isolate product categories (**Accessories, Apparel, Footwear**).

### 2. 💵 Profit from Each Product
* **Visual Type:** Clustered Bar Chart
* **Focus:** Individual SKU profitability.
* **Top Performers:** **Ultraboost 22** ($2,685), **Ultraboost Light** ($2,375), **Predator Freak** ($2,340), and **Copa Sense** ($2,288).

### 3. 🚻 Customer Demographic Breakdown
* **Visual Type:** Donut / Pie Chart
* **Key Ratio:** Men's product sales account for **53.65%** of volume, Female products represent **45.63%**, and Other accounts for **0.72%**.

### 4. 👟 Category Revenue Distribution (Pareto Rule)
* **Visual Type:** Donut Chart
* **Distribution Share:**
  * **Footwear:** 64.95%
  * **Accessories:** 25.19%
  * **Apparel:** 9.86%

### 5. 📈 Age Influence on Quantity & Category
* **Visual Type:** Multi-Category Line Chart
* **Focus:** Customer age distribution across purchasing volume within Footwear, Apparel, and Accessories.

### 6. 📊 Revenue & Sales Volume Trajectory (2023–2025)
* **Visual Type:** Dual-Axis Combo Chart (Column + Line)
* **Focus:** Identifies recurring seasonal spikes and monthly sales fluctuations over a 3-year period.

### 7. 📉 Discount Impact Analysis
* **Visual Type:** Scatter Plot with Profit Callouts
* **Focus:** Evaluates discount rates against net volume/profitability to prove high discounts do not directly scale revenue.

### 8. 🌐 Channel Performance & Geographic Mapping
* **Visual Type:** Pie Chart & Filled Geographic Map
* **Insights:** **Online** stores dominate across all regions at **45.51%** (except Lebanon), with **Egypt** contributing the highest relative regional profit.

---

## 🛠️ Tools Used

* **Power Pivot & Data Modeling:** DAX measures and cross-table KPI aggregation.
* **Excel Data Visualization:** Custom chart layouts, combo charts, scatter plots, and filled map charts.
* **Interactive Controls:** Timeline and multi-select Slicers.
