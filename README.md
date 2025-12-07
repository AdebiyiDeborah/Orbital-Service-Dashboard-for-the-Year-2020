# Orbital-Service-Dashboard-for-the-Year-2020

![My Dashboard](https://github.com/AdebiyiDeborah/Orbital-Service-Dashboard-for-the-Year-2020/blob/main/Orbital%20Dashboard.PNG)
 
## Table of Contents
1. [Introduction](#introduction)
2. [Story of the Data](#story-of-the-data)
3. [Data Splitting and Preprocessing](#data-splitting-and-preprocessing)
4. [Pre Analysis](#pre-analysis)
5. [In Analysis](#in-analysis)
6. [Post Analysis and Insights](#post-analysis-and-insights)
7. [Data Visualization and Charts](#data-visualization-and-charts)
8. [Recommendations and Observations](#recommendations-and-observations)
9. [Conclusion](#conclusion)
10. [References](#references)

## 1. Introduction

The objective of this analysis is to examine the orbital service dataset to uncover profit and sales patterns across regions, segments, and product categories. The goal is to identify key drivers such as top customers, top products, top salespeople, sales trends, and regional performance. These insights will enable management to make data-driven business decisions.

### Problem Being Addressed
While Orbital Service is performing well overall, profitability appears uneven across regions and product segments. This analysis seeks to answer:
- Which regions, product segments, and customers drive Orbital’s performance?
- Where do discounting and operational inefficiencies reduce profit margins?

### Key Datasets and Methodologies
- **Dataset**: Sales dataset sourced from Kaggle.
- **Analytical Tools**:
  - Microsoft Excel Pivot Tables and Pivot Charts
  - Interactive Dashboard for Executive Overview

---

## 2. Story of the Data

### Data Source
The dataset was sourced from Kaggle.

### Data Structure
Each row represents a unique order, with columns ranging from **Order ID** to **Shipping Fee**.

### Important Features and Their Significance:
- **Region**: Identifies geographical performance patterns.
- **Salesperson**: Identifies the effectiveness and efficiency of salespersons.
- **Category**: Different product categories available in the store.
- **Product Name**: Identifies which products generate the most revenue and which contribute little to no revenue.
- **Shipper Name**: Reflects logistics efficiency and its impact on sales.

### Data Limitation or Bias:
- **Missing data on marketing and operational costs**, preventing a full ROI assessment.

---

## 3. Data Splitting and Preprocessing

### Data Cleaning:
- Ensured numeric consistency for all columns.
- Checked for duplicates and verified consistent regional labeling.
- Reformatted order date fields for time-based grouping.

### Data Splitting:
- **Independent Variables**: Customer Name, Address, City, State, Salesperson, Region, Product Name, etc.
- **Dependent Variables**: Revenue, Order ID, Order Date, Customer ID.

### Industry Context:
This analysis is situated within the **logistics and supply chain**, **retail**, and **e-commerce industries**, reflecting multi-channel operations common in large retail chains.

### Stakeholders:
- Executive Management (CEO, CFO)
- Sales and Marketing Teams
- Operations and Logistics
- Regional Managers

### Value to the Industry:
This analysis helps decision-makers identify profitable regions, improve product focus, and streamline operations to align with modern business intelligence needs.

---

## 4. Pre Analysis

### Key Trends:
- **Sales Trend**: December has the peak sum of revenue ($66,642.78), while February has the lowest ($19,985.50).
- **Sales by Product Category**: Beverages lead the sales with $11,057,711, followed by Sauces ($69,000) and Jams, Preserves ($51,541).
- **Sales by Salesperson**: Nancy Freehafer leads with $104,252, followed by Anne Larsen ($93,858) and Andrew Cencini ($67,181).
- **Sales by Customer**: Companies J, H, and F dominate, indicating strong customer involvement.
- **Sales by Region**: North region leads with $141,680 in sales, followed by the South with $93,858.
- **Sales by City**: OR leads with $50,208.35, followed by NK ($67,180.50).

### Initial Insights:
Business growth is driven primarily by consumer demand and top-performing products.

---

## 5. In Analysis

### Unconfirmed Insights and Patterns:
- **Sales Trends**: July, August, and September show slight differences in sales: $27,318.54, $29,921.46, and $31,949.97, respectively.
- **Product**: Canned Meat generates the lowest revenue ($25,465.60).

### Recommendations:
- **Inventory Management**: Investigate the decline in sales between June and July and address the issue with the marketing team.
- **Product Investigation**: Understand why canned meats have low sales and review customer demographics to optimize the product offering.

---

## 6. Post Analysis and Insights

### Key Findings:
- **Salesperson Performance**: Jan Kotas performed exceptionally well among salespersons.
- **Regional Performance**: North region had the highest sales, generating $21,873.31 in December.
- **Product Category**: Beverages had the greatest influence on revenue generation.

---

## 7. Data Visualizations and Charts

### Dashboard Components:
1. **Donut Chart**: Top 3 customers:
   - Company D (41.7%)
   - Company H (31.17%)
   - Company BB (27.13%)
   
2. **Donut Chart**: Top 3 products:
   - Beverages: $11,057,711
   - Sauces: $69,000
   - Jams, Preserves: $51,541
   
3. **Donut Chart**: Sales by Salesperson:
   - Nancy Freehafer: $104,252
   - Anne Larsen: $93,858
   - Andrew Cencini: $67,181
   
4. **Line Chart**: Sales Trend (January to December):
   - December: $66,642.78 (Highest)
   - February: $19,985.50 (Lowest)
   
5. **Radar Chart**: Sales by Region:
   - North: $141,680 (Highest)
   - West: $91,252 (Lowest)
   
6. **Map Chart**: Sales by City

---

## 8. Recommendations and Observations

### Observations:
- **Salespersons**: Andrew Cencini, Jan Kotas, and Nancy Freehafer had their highest sales in June ($11,595.00, $4,928.00, $16,173.56, respectively).
- **Regional Performance**: North region had the highest sales in beverages ($57,873.99), while canned meat generated the lowest sales ($6,338.00).
- **Product Performance**: Beer products had the highest sales in October ($2,464.00) and December ($2,492.00).
- **Top Customer**: Company D emerged as the top customer, using credit cards as their preferred payment method.

### Recommendations:
- Investigate Andrew Cencini’s sales spike in June and apply successful tactics to underperforming months.
- Conduct a thorough investigation into the declining sales from June to August, involving marketing, production, and product teams.
- **Sales Optimization**: Anne Larsen in the South region should request more production of products in the $10–$1010 range, and less in the $4010–$5010 range for better efficiency.
- **Beverage Production**: Increase the production of beverage products as they generate the highest sales.

---

## 9. Conclusion

### Key Learnings:
This analysis confirmed that Orbital Service’s profitability is highly dependent on the **Beverage** category and the **North region**. However, aggressive discounting practices erode profit potential. Sustainable growth requires balancing sales expansion with margin protection.

### Limitations:
The analysis covers a limited time period, restricting longitudinal trends tracking.

### Future Research:
- Explore using **Power BI** for advanced visual analytics and predictive modeling.

---

## 10. References
- **Dataset**: Sales dataset from Kaggle
- **Tools Used**: Microsoft Excel
- **Author**: Adebiyi Deborah Adeola
- **Year of Analysis**: 2025
```


