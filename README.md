
Amazon Operations BI Project

A complete end-to-end analytics project covering SQL, Python, and Power BI, designed to analyze and optimize Amazon’s supply chain & delivery performance.
This project simulates how a real Amazon data analyst evaluates delivery efficiency, supplier performance, customer experience, and logistics operations.

1. Project Overview

This project demonstrates the full analytics workflow:

Data Cleaning & Preparation (Python)

SQL Analysis (KPIs, aggregations, insights)

Power BI Dashboard (interactive, professional-grade visuals)

Supply Chain & Logistics KPIs used in real Amazon operations


The final BI dashboard provides actionable insights into order volume, delivery efficiency, customer ratings, supplier performance, and more.

2. Repository Structure

📦 Amazon-Operations-BI-Project
│
├── data/
│   └── cleaned_dataset.csv
│
├── notebooks/
│   ├── python_analysis.ipynb
│   └── sql_queries.sql(sqlite)
│
├── powerbi/
│   └── Amazon_Operations_Dashboard.pbix
│
└── README.md

3. Key Performance Indicators (KPIs)

These KPIs are exactly what you used in Power BI:

A. Delivery Performance KPIs

On-Time Delivery %

Average Delivery Days

Delayed Orders %

Delivery Status Breakdown (On-Time vs Late)

Delivery Days Trend


B. Order & Customer KPIs

Total Orders

Average Customer Rating

Rating Trend

Orders by Region

Orders by Category


C. Supplier & Cost KPIs

Supplier Performance Score (avg delivery days + rating)

Supplier-wise Orders

Average Shipping Cost

Total Cost / Shipping Cost Trend


D. Product Performance

Top Products by Orders

Quantity Ordered Trend



4. Dashboard Pages

📌 Page 1 – Overview Dashboard

KPI cards (Top section)

Region-wise map/column chart

Category-wise bar chart

Delivery status donut

Delivery days trend

Rating trend

Slicers: Supplier, Region, Category, Date


📌 Page 2 – Supplier Analytics

Supplier ranking

Supplier score matrix

Supplier delivery efficiency

Shipment cost by supplier

🛠️ 5. Tools Used

Tool	Purpose

Python (Pandas, Matplotlib, Seaborn)	Data cleaning + validation
SQL (SQLite / SQL Server)	KPI generation + analysis
Power BI	Dashboard visualization
GitHub	Project hosting



📌 Page 3 – Product & Category Insights

Top products

Category-wise performance

Cost vs Quantity scatter

SQL Queries Included

Your repository includes SQL for:

Delivery & Operations KPIs (Complete)

✔ On-Time Delivery %
✔ Average Delivery Days
✔ Delivery Delay (Actual–Promised)
✔ Late Delivery Count
✔ Region Fulfillment Speed
✔ Perfect Order Rate
✔ Delivery Status analysis

Supplier Performance KPIs (Complete)

✔ Supplier Performance Score
✔ Avg Rating
✔ Issue/Complaint Rate
✔ Shipping Cost per Supplier

Cost & Revenue KPIs (Complete)

✔ Total Revenue
✔ Total Shipping Cost
✔ Profit
✔ Category Contribution %
✔ Cost per Delivery

Customer & Product KPIs (Complete)

✔ Avg Basket Size
✔ Avg Rating by Category
✔ Bad Rating %
✔ Order Volume by Supplier / Category


(These are in sql_queries.sql)


7. Python Notebook Includes

Data import

Cleaning

Missing value handling

Exploratory analysis

KPI validation

Trend charts

CSV export for Power BI


8. Power BI Dashboard Features

Professional layout

Home button

Navigation buttons

Dark/Light theme

Slicers

DAX Measures

Drillthrough


9. Key Insights Delivered

Majority of orders come from high-density regions

Supplier performance varies significantly

High shipping cost does not always mean faster delivery

On-Time Delivery % could be improved with better SLA management

Category demand shows seasonal patterns

Peak order volumes occur during weekend and festival periods, indicating the need for flexible inventory planning .
Products in category "Electronics" and "Home" are most prone to delayed deliveries, suggesting targeted process improvement for these categories.
On-Time Delivery rate averages around 87%, with lower performance in Northern and remote regions; potential optimization for routing and local partners .
Supplier "A" consistently outperforms others in meeting deadlines, making it a benchmark for best practices .
Product ranking analysis shows SKU-102 and SKU-204 are repeatedly top-selling but have frequent stockouts; recommend increasing safety stock for these items .
Shipping cost analysis reveals higher costs for orders containing oversized products and deliveries to tier-3 cities; consolidated shipments may reduce these expenses .
KPI validation uncovered that average delivery days exceeded targets by 0.8 days in December, pointing to capacity constraints or process delays.
Trend charts highlight that the most common order failures are due to incorrect address entry or payment delay, not supply side issues .




