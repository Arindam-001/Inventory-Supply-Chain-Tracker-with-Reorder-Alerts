# Inventory & Supply Chain Tracker with Reorder Alerts

## 📊 Project Overview

The **Inventory & Supply Chain Tracker with Reorder Alerts** is an Excel-based business intelligence project designed to analyze historical retail sales and inventory data and convert it into actionable inventory and supply-chain insights.

The project focuses on identifying inventory risks, monitoring sales performance, understanding demand patterns and supporting data-driven replenishment decisions.

The solution contains two primary dashboards:

1. Executive Dashboard
2. Inventory & Reorder Dashboard

---

## 🎯 Project Objective

The objective of this project is to develop an Inventory & Supply Chain Tracker with Reorder Alerts using historical retail sales and inventory data.

The project analyzes sales, inventory levels, demand forecasts, product categories and regional performance to identify inventory risks and replenishment requirements.

The ultimate goal is to support better inventory planning, reduce stockout and overstocking risks and improve operational decision-making.

---

## 🛠️ Tools & Technologies

- Microsoft Excel
- Excel Tables
- Excel Formulas
- PivotTables
- PivotCharts
- Slicers
- Conditional Formatting
- KPI Cards
- Data Cleaning
- Data Analysis
- Data Visualization
- Forecast Accuracy Analysis
- GitHub

---

## 📁 Dataset

The project uses a historical retail inventory and sales dataset obtained from Kaggle.

The dataset contains information related to:

- Products
- Stores
- Categories
- Dates
- Sales
- Inventory Levels
- Units Sold
- Units Ordered
- Pricing
- Discounts
- Promotions
- Seasonality
- Weather Conditions
- Demand Forecast

The raw dataset was cleaned and transformed before performing the analysis.

---

## 📌 Key Features

### Executive Dashboard

Provides a consolidated view of:

- Total Net Sales
- Gross Sales
- Discount Amount
- Units Sold
- Total Inventory
- Reorder Records
- Reorder Quantity
- Critical Inventory
- Monthly Sales Trend
- Category Performance
- Top Products
- Regional Sales
- Inventory Risk
- Forecast Accuracy

### Inventory & Reorder Dashboard

Focuses on operational inventory decisions:

- Inventory Status
- Critical Inventory
- Low Inventory
- Healthy Inventory
- Overstocked Inventory
- Reorder Records
- Reorder Quantity
- Product-level inventory analysis
- Regional inventory analysis
- Interactive filtering

---

## 📈 Key KPIs

| KPI | Value |
|---|---:|
| Total Net Sales | ₹49,49,71,374.95 |
| Gross Sales | ₹55,02,28,884.91 |
| Discount Amount | ₹5,52,57,509.96 |
| Units Sold | 9,975,582 |
| Total Inventory | 20,063,748 |
| Units Ordered | 8,041,327 |
| Reorder Records | 2,585 |
| Reorder Quantity | 17,293.56 |
| Critical Records | 2,585 |
| Low Records | 35,469 |
| Healthy Records | 18,475 |
| Overstocked Records | 16,571 |
| Forecast Accuracy | ~94% |
| MAE | ~8.30 |

---

## 💡 Key Insights

### 1. Inventory Imbalance

The analysis identifies both low/critical and overstocked inventory records, indicating that the primary opportunity is better inventory allocation rather than simply increasing total inventory.

### 2. Reorder Requirements

The reorder logic identifies 2,585 records requiring replenishment attention.

### 3. Overstocking

16,571 records are classified as overstocked, highlighting an opportunity to review excess inventory and avoid unnecessary procurement.

### 4. Low Inventory

35,469 records are classified as low inventory and should be monitored to prevent them from becoming critical.

### 5. Product Performance

The top-product analysis helps identify products that contribute significantly to net sales and therefore require closer inventory monitoring.

### 6. Regional Performance

Regional sales analysis shows differences in business performance across locations, supporting the need for demand-based regional inventory allocation.

### 7. Forecasting

The defined WMAPE-style forecast accuracy metric is approximately 94%, with an MAE of approximately 8.3 units.

---

## 🎯 Business Decisions

Based on the analysis, the following decisions can be supported:

- Prioritize critical inventory for immediate replenishment.
- Monitor low-stock products proactively.
- Review overstocked products before placing new orders.
- Use forecast demand in replenishment planning.
- Allocate inventory according to regional demand.
- Prepare inventory ahead of seasonal demand periods.
- Closely monitor high-revenue products.
- Evaluate discount strategies against net sales and units sold.
- Review products with high forecast errors.
- Move towards intelligent, demand-based replenishment.

---

## 📸 Dashboard Screenshots

Dashboard screenshots are available in the `screenshots` folder.

### Executive Dashboard

![Executive Dashboard](screenshots/Executive_Dashboard.png)<img width="1091" height="643" alt="IMG-20260830-WA0003" src="https://github.com/user-attachments/assets/bce42777-0ed2-4fac-b521-44bf40c4003b" />


### Inventory & Reorder Dashboard

![Inventory Dashboard](screenshots/Inventory_Dashboard.png) <img width="1237" height="638" alt="IMG-20260830-WA0004" src="https://github.com/user-attachments/assets/0645deca-7a36-4057-94e0-6f6ccfeb72bb" />


---

## 📂 Project Structure

```text
Inventory-Supply-Chain-Tracker/
│
├── README.md
│
├── Excel/
│   └── Inventory_Supply_Chain_Tracker.xlsx
│
├── PPT/
│   └── Inventory_Supply_Chain_Project_Presentation.pptx
│
├── Report/
│   └── Inventory_Supply_Chain_Project_Report.pdf
│
└── screenshots/
    ├── Executive_Dashboard.png
    └── Inventory_Dashboard.png
