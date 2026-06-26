# 📊 Sales & Customer Intelligence Dashboard

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black">
  <img src="https://img.shields.io/badge/DAX-0A66C2?style=for-the-badge">
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white">
  <img src="https://img.shields.io/badge/Data%20Model-Star%20Schema-blue?style=for-the-badge">
</p>

<p align="center">
  <strong>An interactive Business Intelligence solution built with Microsoft Power BI.</strong>
</p>

---

## 🚀 Project Overview

The **Sales & Customer Intelligence Dashboard** is an end-to-end Power BI analytics project that transforms raw business data into meaningful insights.

Using a **Star Schema**, DAX measures, and interactive visualizations, the dashboard enables decision-makers to monitor sales performance, customer trends, regional growth, product performance, and return analysis.

---

# ✨ Features

- ⭐ Star Schema Data Modeling
- 📊 Executive Dashboard
- 📈 Dynamic KPI Cards
- 📅 Time Intelligence (YTD • MTD • YoY)
- 🎯 Interactive Slicers
- 🔍 Cross Filtering
- 📦 Product Performance Analysis
- 👥 Customer Analysis
- 🌍 Regional Analysis
- 🔄 Return Analysis

---

# 🗂️ Dataset

| Table | Description |
|-------|-------------|
| Sales_Fact | Sales transaction data |
| Customer_Dim | Customer details |
| Product_Dim | Product information |
| Region_Dim | Regional information |
| Date_Dim | Calendar table |
| Returns_Fact | Product returns |

---

# 🏗️ Data Model

The project follows a **Star Schema**.

```text
                 Date_Dim
                     │
                     │
Product_Dim ── Sales_Fact ── Customer_Dim
                     │
                     │
              Returns_Fact
                     │
                     │
                Region_Dim
```

---

# 📊 Dashboard Pages

## 📌 Executive Dashboard

- Total Sales
- Total Orders
- Total Customers
- Total Returns
- Return Rate
- Monthly Sales Trend
- Sales by Region
- Sales by Category
- Top Products

---

## 👥 Customer Analysis

- Customer Distribution
- Customer Segmentation
- Top Customers
- Customer Sales

---

## 📦 Product Analysis

- Top Performing Products
- Bottom Performing Products
- Category Performance
- Product Profitability

---

## 🌍 Regional Analysis

- Regional Sales
- Regional Profit
- Regional Returns
- Performance Comparison

---

## 📅 Time Analysis

- Monthly Sales
- Quarterly Sales
- Yearly Sales
- Sales YTD
- Sales MTD
- YoY Growth

---

# 📈 Key KPIs

- 💰 Total Sales
- 🛒 Total Orders
- 👤 Total Customers
- 📦 Units Sold
- 🔄 Total Returns
- 📉 Return Rate
- 📊 Average Order Value
- 📈 YoY Growth
- 📅 Sales YTD
- 📆 Sales MTD

---

# 🧮 DAX Measures

- Total Sales
- Total Orders
- Total Customers
- Total Units Sold
- Total Returns
- Return Rate
- Average Order Value
- Sales YTD
- Sales MTD
- Previous Year Sales
- YoY Growth %

---

# 🛠️ Tools & Technologies

- Microsoft Power BI Desktop
- DAX
- Power Query
- Microsoft Excel
- Star Schema Data Modeling

---

# 🖼️ Dashboard Preview

> Add screenshots inside the **images** folder.

## Executive Dashboard

```md
![Executive Dashboard](images/executive-dashboard.png)
```

## Customer Analysis

```md
![Customer Analysis](images/customer-analysis.png)
```

## Product Analysis

```md
![Product Analysis](images/product-analysis.png)
```

## Regional Analysis

```md
![Regional Analysis](images/regional-analysis.png)
```

## Time Analysis

```md
![Time Analysis](images/time-analysis.png)
```

---

# 📁 Project Structure

```text
Sales-Customer-Intelligence-Dashboard
│
├── PR..Final.pbix
├── FinalProject_Dataset.xlsx
├── README.md
│
├── images
│   ├── executive-dashboard.png
│   ├── customer-analysis.png
│   ├── product-analysis.png
│   ├── regional-analysis.png
│   └── time-analysis.png
│
└── assets
```

---

# 🚀 Getting Started

1. Clone this repository.
2. Open **PR..Final.pbix** in Microsoft Power BI Desktop.
3. Refresh the data if required.
4. Explore the dashboard using filters and slicers.

---

# 💼 Business Insights

- Identify high-performing products.
- Track customer purchasing behavior.
- Compare regional sales performance.
- Analyze return trends.
- Monitor business KPIs over time.
- Support data-driven business decisions.

---

# 🔮 Future Enhancements

- AI Visuals
- Sales Forecasting
- Drill-through Reports
- Bookmarks & Navigation
- Mobile Layout
- Row-Level Security (RLS)
- Power BI Service Deployment

---

# 👨‍💻 Author

**Prince**

AI & Data Science Student

**Skills**

- Power BI
- SQL
- Excel
- Python
- Data Analytics

---

## ⭐ If you like this project

If this project helped you or inspired you, consider giving it a ⭐ on GitHub.

It really helps and motivates me to build more data analytics projects.