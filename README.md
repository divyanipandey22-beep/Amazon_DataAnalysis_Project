
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

Total Orders

Average Delivery Days

On-Time %

Category & Region Aggregations

Supplier Performance

Product Ranking

Shipping Cost Analysis


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

10. How to Run This Project

Step 1: Clone Repo

git clone https://github.com/yourusername/Amazon-Operations-BI-Project.git

Step 2: Open Python Notebook

Run python_analysis.ipynb to inspect or modify data.

Step 3: Open Power BI File

Open Amazon_Operations_Dashboard.pbix
Make sure your dataset path is correct.


