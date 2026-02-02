# Sales & Profitability Analysis Dashboard (Excel + Power BI)

## 📌 Business Problem
The objective of this project was to analyze sales performance and profitability across product categories and regions, identify loss-making areas, evaluate discount impact, and present actionable insights using Excel analysis and an interactive Power BI dashboard.

This project follows an **end-to-end analytics workflow**:  
Excel exploration → Pivot table analysis → Power BI modeling & visualization.

---

## 📊 Dataset
**Sample Superstore Dataset**

The dataset contains order-level transactional data including:
- Order and shipping dates  
- Product category and sub-category  
- Region and customer identifiers  
- Sales, profit, discount, and quantity  

Each row represents **one product line item within an order**.

---

## 🛠 Tools & Skills Used
- **Excel** (Tables, Pivot Tables, Power Query, data cleaning)
- **Power BI** (Data modeling, DAX, dashboards, drill-through)
- **DAX** (Measures, ratios, filter context handling)
- **SQL concepts** (analytical logic translated conceptually)
- **Data Analysis & Business Insights**

---

## 📊 Excel Data Cleaning & Preparation
Before visualization, the data was cleaned and prepared in Excel:

- Converted raw data into **Excel Tables** for structured analysis.
- Validated and corrected data types (dates, currency, numeric fields).
- Created helper columns:
  - **Profit Flag** (Profit vs Loss)
  - **High Discount Flag**
  - **Shipping Days** (Ship Date – Order Date)
- Used **Power Query** to automate cleaning steps and enable refreshable workflows.

This ensured the dataset was analysis-ready and reliable.

---

## 📈 Excel Pivot Table Analysis

### 1️⃣ Sales Trend Analysis
- Built pivot tables to analyze **monthly and yearly sales trends**.
- Grouped Order Date by **Year and Month** to identify seasonality.
- Used slicers to enable **region-wise filtering**.

**Insight:**  
Sales show clear seasonality with stronger performance toward the end of the year.

---

### 2️⃣ Profitability Analysis
- Analyzed **Sales and Profit by Category and Sub-Category**.
- Identified that **Furniture generates high revenue but overall losses**.
- Used Profit Flag to isolate loss-making segments.

**Insight:**  
High revenue does not necessarily translate to profitability; losses are concentrated in specific sub-categories.

---

### 3️⃣ Discount Impact Analysis
- Analyzed **Average Profit by Discount bands**.
- Observed that discounts above ~30% consistently resulted in negative profit.

**Insight:**  
Deep discounting erodes margins without proportional sales growth, indicating a need for discount capping.

---

### 4️⃣ Operational (Shipping) Analysis
- Evaluated **Average Shipping Days by Region**.
- Compared shipping delays with profitability.

**Insight:**  
Regions with longer shipping times tend to show lower profitability, suggesting operational inefficiencies.

---

## 📊 Power BI Dashboard Overview
After Excel exploration, insights were translated into a scalable Power BI dashboard.

### Key Features:
- Executive KPI cards: **Total Sales, Total Profit, Profit Margin**
- Sales trend visualization using a **custom Date table**
- Category-level profitability bar charts
- Region and category slicers for self-service filtering
- Drill-through pages for **category-level deep dives**
- Back-button navigation for usability

---

## 📐 Data Modeling & DAX Highlights
- Implemented a **star-schema model** with a dedicated Date table.
- Created reusable DAX measures:
  - `Total Sales`
  - `Total Profit`
  - `Profit Margin`
- Handled divide-by-zero scenarios and filter context explicitly.
- Used drill-through to avoid cluttering the main dashboard while enabling deeper analysis.

---

## 🔍 Key Business Insights
- Technology is the strongest profit driver, while Furniture contributes disproportionately to losses.
- Discounts above ~30% significantly reduce average profit without meaningful sales uplift.
- Losses are concentrated in specific sub-categories rather than entire categories.
- Drill-through analysis enables stakeholders to move from KPIs to detailed insights seamlessly.

---

## 🚀 What I’d Do Next
- Add customer-level analysis to evaluate customer profitability and retention.
- Automate data refresh and connect to a live data source.
- Extend the dashboard with role-based views for different stakeholders.

---

## 📎 Project Artifacts
- 📂 Excel cleaning steps and pivot analysis (documented with screenshots)
- 📊 Power BI dashboard screenshots
- 📁 Structured GitHub repository for easy review

---

## 📣 Summary
This project demonstrates **end-to-end data analytics skills**, from raw data cleaning and Excel-based exploration to scalable Power BI dashboards and business-driven insights. It reflects real-world analyst workflows used in professional environments.
