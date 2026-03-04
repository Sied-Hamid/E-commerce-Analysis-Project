# 🛒📊 E-Commerce Sales Analysis

![Dashboard page 1](/Image/dashboard_page.png)

[view interactive dashboard here on the powerbi service](https://bit.ly/E-commerce_project)

### Excel + Power BI | End-to-End Analytics Case Study

# 🔍 Overview

End-to-end e-commerce analytics project using **Excel for data preparation and Power BI for modeling, DAX, and interactive dashboards**.
The project answers real business questions around revenue performance, product contribution, customer behavior, and market trends.

# 🎯 Business Goal

- Enable stakeholders to:

- Monitor key performance metrics
- Identify top markets and products

- Understand device-based purchasing behavior

- Track revenue and pricing trends over time

# 🛠 Tools

- **Excel**: Data cleaning, Power Query, validation pivots

- **Power BI**:  DAX measures, interactive dashboard

# 🔄 Workflow (End-to-End)

### Excel

- Cleaned and standardized raw transaction data

![Dashboard Page 2](/image/power_query_table.png)

- Validated metrics product performance sample using pivot tables

![Dashboard Page 3](/image/pivot_table.png)

- Prepared analysis-ready tables   
### Power BI

- Created core KPIs using DAX

- Designed executive-focused dashboard

## 📐 Core DAX Measures
```DAX
Total Revenue = SUM(workingsheet[total amount])

Total Orders = DISTINCTCOUNT(workingsheet[user ID])

Total Units = SUM(workingsheet[quantity])

Average Order Value (AOV) =
DIVIDE([Total Revenue], [Total Orders])

Avg Discount Rate =
AVERAGE(workingsheet[Discount Rate])
```
### 📊 Key KPIs

- Total Revenue: £126M

- Total Orders: 100K

- Average Order Value: £1.26K

- Average Discount Rate: 25%

# ❓ Business Questions Answered

### How is the business performing overall?
-  Strong revenue and high AOV indicate healthy monetization.

### Which countries drive the most revenue?
- US, UK, and Canada are top-performing markets.

### Which products contribute most to revenue?
- Books, T-shirts, Smartphones, and Watches lead sales.

### How do customers shop?
- Revenue is driven primarily through Mobile and Desktop.

### Are there seasonal trends?
- Monthly revenue and AOV fluctuate, indicating seasonality and pricing effects.

# 📈 Business Value

- Executive-ready performance monitoring

- Market and product prioritization

- Device optimization insights

- Revenue trend visibility

### 🧠 Key Takeaways

Clean data enables accurate insights

Excel + Power BI reflect real-world analytics workflows

Strong dashboards answer business questions—not just show charts

## 🚀 Conclusion

A portfolio-ready analytics project demonstrating practical data cleaning, modeling, KPI development, and business-focused visualization using Excel and Power BI.
