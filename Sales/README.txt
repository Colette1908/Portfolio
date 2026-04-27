# Sales Dashboard | Power BI Portfolio Project

A professional end-to-end sales analytics project built in Power BI to transform raw transaction data into clear business insights for decision-making.

---

# Project Overview

This dashboard was designed to help management monitor sales performance, profitability, customer trends, and regional performance through interactive reporting.

The project demonstrates practical analytics skills including:

- Data cleaning
- Data modelling
- KPI development
- DAX calculations
- Dashboard design
- Business storytelling
- Interactive reporting
- Tooltip pages
- Portfolio presentation

---

# Business Problem

Many businesses store sales data in spreadsheets but struggle to answer important questions quickly:

- Which region generates the most revenue?
- Which products are most profitable?
- Who are the top customers?
- How is revenue changing month to month?
- Which categories drive margin?
- Where are growth opportunities?

Manual reporting is slow and limits decision-making.

---

# Solution

Built an interactive Power BI dashboard that converts raw sales data into actionable insights through dynamic visuals and KPI reporting.

---

# Tools Used

- Power BI  
- Power Query  
- DAX  
- Excel / CSV  

---

# Dataset

Synthetic sales dataset created for portfolio purposes.

### Fields Included

- OrderID  
- OrderDate  
- CustomerName  
- Product  
- Category  
- Region  
- Salesperson  
- Quantity  
- UnitPrice  
- Revenue  
- Cost  
- Profit  

---

# Dashboard Pages

# Page 1 – Executive Sales Overview

Provides a high-level view of business performance.

### KPI Cards

- Total Revenue  
- Total Profit  
- Number of Orders  
- Average Order Value  
- Profit Margin %  

### Visuals

- Revenue by Month  
- Revenue by Region  
- Top Products Sold  
- Profit by Category  
- Top Customers by Revenue  
- Detailed Sales Table  
- Collapsible Filter Panel  

---

# Page 2 – Sales Performance Dashboard

Provides deeper performance analysis.

### KPI Cards

- Best Salesperson  
- Lowest Salesperson  
- Best Region  
- Best Product  
- Growth %  

### Visuals

- Top Salespeople by Revenue  
- Profit by Product  
- Revenue vs Profit Scatter Plot  
- Monthly Growth Trend  

---

# Advanced Features

- Dynamic KPI cards  
- Custom formatting  
- Collapsible filter panel  
- Dynamic subtitles  
- Custom tooltip pages:
  - Region Tooltip
  - Customer Tooltip
  - Product Tooltip

---

# Example Insights

- Gauteng generated the highest revenue  
- Electronics delivered the strongest profit  
- Vision Group was the top customer  
- Revenue peaked in January  
- Profit margin remained strong overall  

---

# Example DAX Measures

## Total Revenue

Total Revenue = SUM(Sales[Revenue])
Total Profit = SUM(Sales[Profit])
Orders = DISTINCTCOUNT(Sales[OrderID])
Profit Margin % =
DIVIDE([Total Profit], [Total Revenue])

* Files Included

Sales/
│── README.md
│── Sales_Dashboard.pbix
│── data/
│   │── raw/
│   		|── sales.txt
│── processed/
│   		├── sales.xlsx
│── images/
│   ├── sales_dashboard_no filter.png
│   ├── sales_dashboard_tooltip.png
│   ├── sales_dashboard_tooltip.png
│   ├── sales_dashboard_tooltip.png
│   ├── tooltip_customer.png
│   ├── tooltip_product.png
│   ├── tooltip_region.png
│── dax/
│   ├── measures.txt

Screenshots
Add dashboard screenshots here.
Example:

Why This Project Matters
This project demonstrates the ability to:

* Build executive dashboards
* Analyse revenue and profitability
* Design professional visuals
* Use DAX for business metrics
* Improve user experience with interactivity
* Communicate insights clearly

About Me
Data analyst with extensive business and management experience focused on practical analytics solutions that improve decision-making.

Connect
www.linkedin.com/in/colette-van-rooyen-a062a399
* https://github.com/Colette1908/Portfolio
* https://github.com/Colette1908

License
Portfolio project for demonstration purposes.
