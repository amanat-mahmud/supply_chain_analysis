# 📊 Supply Chain Analysis: Inventory Optimization

## 📕 Table of Contents
- [Problem Statement](#-problem-statement)
- [Objective](#-objective)
- [Tools Used](#%EF%B8%8F-tools-used)
- [Dataset Overview](#-dataset-overview)
- [Key Findings](#-key-findings)
- [Recommendations](#-recommendations)
- [Project Presentation](#-project-presentation)
- [Project Learnings](#-project-learnings)
- [Installation and Usage](#-installation-and-usage)
- [Dashboard](#-dashboard)

## ❓ Problem Statement
The company faces challenges in optimizing inventory management, leading to overstocking or understocking issues. This inefficiency impacts storage costs, capital tied up in inventory, and the ability to meet customer demand promptly. Current analysis lacks focus on critical inventory metrics needed for informed stocking decisions.

## 🎯 Objective
Enhance supply chain efficiency by optimizing inventory management. This involves identifying key products to stock, determining optimal reorder points, and ensuring timely fulfillment of customer orders. The goal is to reduce storage costs, prevent stockouts, and improve overall customer satisfaction.

## 🛠️ Tools Used
- **Analytical & Visual:**  Microsoft Excel\
  <img width="96" height="96" src="https://img.icons8.com/color/96/microsoft-excel-2019--v1.png" alt="microsoft-excel-2019--v1"/>
- **Presentation:** Microsoft Power Point\
  <img width="96" height="96" src="https://img.icons8.com/fluency/96/microsoft-powerpoint-2019.png" alt="microsoft-powerpoint-2019"/>

## 📅 Dataset Overview
- **Data source:** Internet
- **Time period:** 2015-2018
- **Data size:** 
  - Sales_Shipment_Data Table (180519,46)
  - Inventory_stock_Data table (118,11)
- **Key columns:** Sales per customer, Customer Segment, Order Status, Class, Shipping Mode, Current Stock, Order Profit Per Order, Order Item Quantity, Sales Per Customer, Order Item Discount, order-now
- **Calculated columns:** stock_item_price, product_class, sales_compared_to_prev_year
- [**Data Model**](https://github.com/amanat-mahmud/supply_chain_analysis/blob/main/data%20model.png)

## 🔎 Key Findings
- Inventory value: $1.59M
- Total sales: $33.05M
- Stock units: 18.97K
- "Small value, large number" product class accounts for the highest stocked items
- Consumer segment generates over half of total sales and profit
- "High value, small number" class contributes to more than half of the sales
- Standard shipping class dominates in sales and customer volume
- Profit and sales have been declining year-over-year
- Late deliveries consistently account for half of all shipments across years

## 💡 Recommendations
1. Optimize inventory levels for the "small value, large number" class
2. Enhance strategies for the consumer segment while exploring growth in other segments
3. Reevaluate discounting strategy across segments
4. Address declining profits and sales through various measures
5. Streamline order fulfillment processes
6. Prioritize on-time deliveries
7. Develop a balanced discount strategy
8. Focus on maintaining and enhancing the "high value, small number" class performance

## 📌 Project Presentation
### Video Presentation
[![ Supply Chain Analysis Presentation](https://github.com/amanat-mahmud/supply_chain_analysis/blob/main/cover.png)](https://www.linkedin.com/posts/amanat-mahmud_dataanalysis-businessintelligence-datadrivendecisions-activity-7222566931113893888-HQeQ/)

### Slides
The detailed presentation slides for this project can be found [here](https://github.com/amanat-mahmud/supply_chain_analysis/blob/main/slide.pdf)

## 🧠 Project Learnings
1. Data Loading and Transformations.
2. Pivot table analysis.
3. Power Query and DAX.
4. Data modeling.
5. Data visualization.
6. Importance of data quality.
7. Data storytelling.
8. Sharpened analytical and problem-solving abilities.
9. Strengthened strategic planning and presentation skill.
10. Enhanced communication skills.


## 💻 Installation and Usage
- Microsoft Excel

## Dashboard
<img src="https://github.com/amanat-mahmud/supply_chain_analysis/blob/main/dashboard_ss.png">
