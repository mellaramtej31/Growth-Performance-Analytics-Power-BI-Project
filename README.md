# Growth Performance & Sales Forecasting Dashboard

## 📊 About The Project

This project presents a comprehensive Business Intelligence dashboard built using Power BI to analyze and visualize sales performance for a retail business. The dashboard provides a holistic view of key business metrics across various dimensions and includes a predictive forecasting model to estimate future sales.

The solution is divided into two main sections:
1.  **Dashboard:** An interactive overview of historical performance, focusing on sales, profit, and customer behavior.
2.  **Forecasting:** A time-series analysis graph that projects sales for the next 15 days.

This tool is designed for business managers, sales teams, and data analysts to derive actionable insights, monitor growth, and make data-driven decisions.

---

## ✨ Dashboard Features

### Main Dashboard Page

The primary dashboard offers a snapshot of the company's health and performance:

* **Key Performance Indicators (KPIs):** At-a-glance cards display crucial metrics:
    * **Total Sales:** $1.57M
    * **Total Quantity:** 22.32K units
    * **Total Profit:** $0.18M
    * **Average Delivery Days:** 3.93 days
* **Regional & Segment Performance:** Donut charts break down sales by Region, Customer Segment, and Payment Mode, quickly identifying top-performing areas.
* **Time-Series Analysis:** Year-over-year line charts for both `Monthly Profit` and `Monthly Sales` compare performance between 2019 and 2020, highlighting seasonal trends and growth patterns.
* **Product & Logistics Insights:** Bar charts provide detailed breakdowns of sales by `Category`, `Sub-Category`, and `Ship Mode`.
* **Geospatial Analysis:** An interactive map visualizes `Sales and Profit by State`, allowing for geographic exploration of performance hotspots.
* **Interactive Filtering:** Users can dynamically filter the entire dashboard by `Region` (Central, East, South, West) to drill down into specific areas.

### Forecasting Page

This page focuses on predictive analytics:

* **15-Day Sales Forecast:** A time-series line graph displays historical sales data and projects `Sum of Sales` for the upcoming 15 days, visualized with confidence intervals.
* **State-Level Sales View:** A supplementary bar chart ranks states by total sales, providing context to the overall forecast.

---

## 📈 Key Insights & Metrics

This analysis uncovered several key insights:

* **Top Performing Region:** The **West** region is the largest contributor to sales, accounting for **33%** of the total revenue.
* **Primary Customer Segment:** The **Consumer** segment is the most significant, driving **49%** of all sales.
* **Product Category Dominance:** **Technology** and **Office Supplies** are the leading product categories by sales volume.
* **Seasonal Peaks:** The Year-over-Year charts indicate a significant increase in both sales and profit towards the end of the calendar year, particularly in November and December.
* **Predictive Power:** The forecasting model allows the business to anticipate sales fluctuations, enabling better inventory management and targeted marketing efforts.

---

## 🛠️ Tools Used

* **Microsoft Power BI:** For data modeling, analysis, and dashboard development.
* **DAX (Data Analysis Expressions):** Used for creating custom measures and calculated columns.
* **Power Query:** For data cleaning, transformation, and ETL processes.

---

## 💾 Data Source

The analysis was performed on a sample sales dataset (similar to the common "Superstore" dataset). The dataset contains transactional data with columns such as:
* `Order Date`
* `Region`, `State`
* `Segment`, `Category`, `Sub-Category`
* `Sales`, `Quantity`, `Profit`
* `Ship Mode`, `Payment Mode`

---

