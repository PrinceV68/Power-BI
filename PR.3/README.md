# 📊 Sales & Customer Intelligence Dashboard

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/DAX-0066CC?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white"/>
  <img src="https://img.shields.io/badge/Star%20Schema-4285F4?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Interactive-Dashboard-blueviolet?style=for-the-badge"/>
</p>

<p align="center">
  <b>An Interactive Business Intelligence Dashboard built with Microsoft Power BI</b>
</p>

---

## 📌 Overview

The **Sales & Customer Intelligence Dashboard** is an end-to-end Power BI Business Intelligence project that transforms raw sales data into meaningful insights.

The project implements professional data modeling, DAX calculations, interactive visualizations, and business KPIs to help analyze sales performance, customer behavior, regional trends, product performance, and return analysis.

---

# ✨ Features

- ⭐ Star Schema Data Model
- 📊 Interactive Dashboard
- 📈 Executive KPIs
- 📅 Time Intelligence (YTD, MTD, YoY)
- 🎯 Dynamic Slicers
- 🔍 Cross Filtering
- 📦 Product Analysis
- 👥 Customer Insights
- 🌍 Regional Analysis
- 🔄 Return Analysis
- ⚡ Optimized DAX Measures

---

# 📂 Dataset

The dashboard uses multiple related tables following a Star Schema.

| Table | Description |
|--------|-------------|
| Sales_Fact | Sales Transactions |
| Customer_Dim | Customer Information |
| Product_Dim | Product Details |
| Region_Dim | Regional Information |
| Date_Dim | Calendar Table |
| Returns_Fact | Return Records |

---

# 🏗️ Data Model

```
                Date_Dim
                    │
                    │
Product_Dim ─ Sales_Fact ─ Customer_Dim
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
- Customer Segments
- Top Customers
- Customer Sales

---

## 📦 Product Analysis

- Top Products
- Bottom Products
- Product Categories
- Product Profitability

---

## 🌍 Regional Analysis

- Region-wise Sales
- Region-wise Returns
- Regional Profit
- Regional Performance

---

## 📅 Time Analysis

- Monthly Sales
- Quarterly Sales
- Yearly Sales
- YTD Sales
- MTD Sales
- YoY Growth

---

# 📈 Key KPIs

| KPI | Description |
|------|-------------|
| Total Sales | Overall Revenue |
| Total Orders | Number of Orders |
| Total Customers | Customer Count |
| Units Sold | Quantity Sold |
| Total Returns | Returned Orders |
| Return Rate | Return Percentage |
| Average Order Value | Revenue per Order |
| Sales Growth | Growth Analysis |

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

- Microsoft Power BI
- Microsoft Excel
- DAX
- Power Query
- Data Modeling
- Star Schema

---

# 🖼️ Dashboard Preview

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

```
Sales-Customer-Intelligence-Dashboard
│
├── Dashboard.pbix
├── Dataset.xlsx
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

# 🚀 How to Run

1. Download this repository.
2. Open the `.pbix` file using Microsoft Power BI Desktop.
3. Refresh the dataset if necessary.
4. Explore the dashboard using slicers and filters.

---

# 💡 Business Insights

- Identify high-performing products.
- Analyze regional sales performance.
- Understand customer purchasing behavior.
- Monitor return trends.
- Compare monthly and yearly sales performance.
- Track key business KPIs.

---

# 🔮 Future Improvements

- AI Insights
- Forecasting
- Drill Through Pages
- Bookmarks
- Mobile Layout
- Row-Level Security
- Power BI Service Deployment

---

# 👨‍💻 Author

**Prince**

AI & Data Science Student

Power BI • SQL • Excel • Python

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

It helps support future projects and encourages continued development.