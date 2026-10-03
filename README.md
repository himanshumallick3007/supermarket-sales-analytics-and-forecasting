# Super Store Sales Analysis & 15-Day Time Series Forecasting Dashboard

## 📌 Project Overview
The objective of this project is to leverage business intelligence and data analytics techniques to evaluate historical sales performance and deliver actionable business insights[cite: 1]. Using **Power BI**, this project implements interactive KPI tracking, multidimensional category/shipping breakdown, regional analysis, and a **15-day time series sales forecast** to support data-driven decision-making and inventory planning[cite: 1, 2, 3].

---

## 📸 Dashboard Previews

### 1. Super Store Sales Performance Dashboard
![Sales Dashboard](sales_dashboard.png)

### 2. 15-Day Time Series Sales Forecasting & State Trends
![Sales Forecast Dashboard](sales_forecast_dashboard.png)

---

## 🎯 Key Objectives
- **Dashboard Creation**: Design an intuitive, interactive Power BI report with dynamic slicers (Region, Category, Segment) to explore data across granular dimensions[cite: 2, 4].
- **Data Analysis**: Identify revenue trends, profit margins, shipping efficiency, and high-performing product segments[cite: 2, 4].
- **Time Series Forecasting**: Apply historical sales trends over multiple years to generate a reliable **15-day forward sales forecast**[cite: 1, 2, 3].
- **Actionable Business Insights**: Enable supermarket stakeholders to optimize stock levels, refine logistics choices, and target top-performing customer segments[cite: 2].

---

## 📊 Key Metrics & Insights

### Core Business KPIs
- **Total Sales**: $252K[cite: 4]
- **Total Profit**: $27K[cite: 4]
- **Quantity Sold**: 3,529 units[cite: 4]
- **Average Delivery Time**: 4 days[cite: 4]

### Breakdown & Distribution
- **Payment Method**: Cash on Delivery (COD) represents the largest share at **~43.6%**, followed by Online transactions (**~37.2%**) and Cards (**~19.1%**)[cite: 4].
- **Customer Segments**: Consumer segment drives over half of overall demand (**~53.6%**), followed by Corporate (**~29.8%**) and Home Office (**~16.6%**)[cite: 4].
- **Shipping Modes**: **Standard Class** dominates order volume (~48K sales), significantly outpacing Second Class (~21K), First Class (~13K), and Same Day (~6K)[cite: 4].
- **Product Categories**: Office Supplies leads revenue (~$100K), followed by Technology (~$79K) and Furniture (~$73K), with Phones, Tables, and Storage leading subcategories[cite: 4].
- **Geographic Distribution**: California, New York, and Texas rank as top revenue-generating states[cite: 3].

---

## 🛠️ Tech Stack & Tools
- **Business Intelligence Tool**: Microsoft Power BI (Power Query, DAX, Native Time Series Forecasting Visuals)[cite: 1, 2]
- **Data Source**: Superstore / Supermarket Transactional Dataset[cite: 1, 3]
- **Techniques**: Time Series Analysis, Exploratory Data Analysis (EDA), Data Modeling, KPI Dashboarding[cite: 1, 2]

---

## 📂 Repository Structure
```text
├── datasets/
│   └── SuperStore_Sales_Data.csv
├── dashboard/
│   ├── SuperStore_Sales_Dashboard.pbix
│   ├── sales_dashboard.pdf
│   └── sales_forecast.pdf
├── images/
│   ├── sales_dashboard.png
│   └── sales_forecast_dashboard.png
└── README.md
