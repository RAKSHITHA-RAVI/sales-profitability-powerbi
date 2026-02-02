# Sales & Profitability Analysis Dashboard (Power BI)

## 📌 Business Problem
Analyze sales performance and profitability across product categories and regions,
identify loss-making areas, and present actionable insights using an interactive dashboard.

## 📊 Dataset
Sample Superstore dataset containing order-level sales, profit, discount, and shipping data.

## 🛠 Tools & Skills
- Power BI (DAX, Power Query, Data Modeling)
- Excel (data cleaning & validation)
- SQL (conceptual analytics logic)

## 📈 Dashboard Overview
![Dashboard Overview](dashboard/overview.png)

## 🔍 Key Insights
- Technology is the most profitable category, while Furniture generates high revenue but negative profit.
- Discounts above ~30% significantly reduce average profit without proportional sales growth.
- Losses are concentrated in specific sub-categories rather than across entire categories.
- Drill-through analysis enables deeper category-level investigation without cluttering the main view.

## 🧠 What I Did (Technical Highlights)
- Built a star-schema model with a custom Date table
- Created DAX measures for Total Sales, Total Profit, and Profit Margin
- Implemented slicers and drill-through pages for interactive analysis
- Handled data quality issues such as mixed date formats and ID typing

## 🚀 What I’d Do Next
- Add customer-level analysis to evaluate customer profitability
- Automate data refresh and expand the dashboard with role-based views
