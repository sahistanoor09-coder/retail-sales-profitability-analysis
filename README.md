# retail-sales-profitability-analysisThis retail sales analytics project built in Excel uses 1,000 dummy transactions from 2010–2017. It explores revenue, cost, profit, and profit margin across countries, regions, product categories, and online/offline channels, with summary tables, trend analysis, comparisons, and full dashboard visuals to highlight business performance and insights.This retail sales analytics project built in Excel uses 1,000 dummy transactions >

# 📊 Retail Sales & Profitability Analysis

## 📌 Project Overview

This project focuses on analysing retail sales data to understand business performance, revenue generation, cost distribution, and profitability across different regions, countries, product categories, and sales channels.

The project uses a Dummy Store retail transaction dataset containing **1,000 transactions from 2010 to 2017**. Microsoft Excel is used to organise, analyse, summarise, and visualise the data through summary tables, charts, and an interactive-style dashboard.

The primary goal is to transform raw sales data into meaningful business insights that can support better decision-making.

---

## 🎯 Project Objectives

- Analyse overall sales revenue, total cost, and profit.
- Identify the highest-performing product categories.
- Compare revenue and profitability across geographical regions.
- Analyse sales performance across online and offline channels.
- Understand yearly revenue trends and business performance.
- Identify patterns and opportunities for improving profitability.
- Present key business insights through visualisations and dashboards.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Excel | Data analysis and visualisation |
| Pivot Tables | Data summarisation and aggregation |
| Charts | Visual representation of business performance |
| Dashboard | Business insights and KPI presentation |
| Git | Version control |
| GitHub | Project hosting and documentation |

---

## 📂 Dataset Information

The dataset contains 1,000 records and 15 columns.

### Dataset Columns

| Column Name | Description |
|---|---|
| Region | Geographical sales region |
| Country | Country where the order was placed |
| Item Type | Category of product sold |
| Rep Name | Sales representative name |
| Sales Channel | Online or Offline sales channel |
| Order Priority | Priority code assigned to the order |
| Order Date | Date when the order was placed |
| Order ID | Unique order identification number |
| Ship Date | Date when the order was shipped |
| Units Sold | Quantity of products sold |
| Unit Price | Selling price per unit |
| Unit Cost | Cost per unit |
| Total Revenue | Total sales revenue generated |
| Total Cost | Total cost of products sold |
| Total Profit | Profit generated from the transaction |

### Dataset Dimensions

- Total Records: 1,000
- Total Columns: 15
- Unique Countries: 185
- Sales Regions: 7
- Product Categories: 12
- Sales Channels: 2
- Order Period: January 2010 – July 2017

---

## 📈 Key Performance Indicators (KPIs)

The following KPIs were identified from the dataset:

| KPI | Value |
|---|---:|
| Total Revenue | 1,327,321,840.33 |
| Total Cost | 936,119,228.77 |
| Total Profit | 391,202,611.56 |
| Profit Margin | 29.47% |
| Total Orders | 1,000 |

**Profit Margin Formula:**

Profit Margin = (Total Profit / Total Revenue) × 100

*Note: The workbook does not specify the currency of these financial values.*

---

## 🔍 Key Business Insights

### 1. Revenue Analysis
- Total revenue generated across all transactions is approximately 1.327 billion.
- The highest annual revenue was recorded in 2014.
- Revenue performance varies across the years.

### 2. Regional Performance
- Sub-Saharan Africa generated the highest revenue among all regions.
- Europe was the second-highest revenue-generating region.
- North America recorded the lowest revenue among the seven regions.

### 3. Product Category Analysis
- Office Supplies generated the highest revenue.
- Household products ranked second in revenue generation.
- Cosmetics also contributed significantly to total revenue.
- Fruits generated the lowest revenue among the product categories.

### 4. Sales Channel Analysis
- The Offline sales channel generated higher total profit than the Online channel.
- Offline sales contributed approximately 207.89 million in profit.
- Online sales contributed approximately 183.32 million in profit.

### 5. Yearly Sales Trends
- 2014 recorded the highest annual revenue.
- Revenue declined after 2014 through 2016.
- 2017 contains data only up to July 26, so it should not be directly compared with complete calendar years.

---

## 📊 Dashboard & Visualisation

The Excel workbook includes a dashboard with four charts to present important business metrics and sales performance.

The project also contains separate analytical sheets covering:

- Annual Revenue, Cost & Profit
- Sales Channel Profitability
- Region-wise Revenue Analysis
- Country-wise Revenue Summary
- Product Category Revenue Analysis
- Yearly Revenue Trends

These visualisations help understand business performance and identify important patterns in the sales data.

---

## 📁 Repository Structure

```text
retail-sales-profitability-analysis/
│
├── data/
│   └── dummy_store_sales_analysis.xlsx
│
├── docs/
│   ├── DATA_DICTIONARY.md
│   └── PROJECT_ANALYSIS.md
│
├── README.md
│
└── .gitignore
```

---

## ✅ Data Quality Checks & Limitations

- Verified that all 1,000 transaction records have complete values.
- Checked that all Order IDs are unique.
- Verified Total Revenue = Units Sold × Unit Price.
- Verified Total Cost = Units Sold × Unit Cost.
- Verified Total Profit = Total Revenue − Total Cost.
- No calculation mismatches were identified.

**Important limitations:**

- Currency information is not provided in the source workbook.
- The 2017 dataset is incomplete.
- All 1,000 records contain distinct sales representative names, limiting meaningful repeated-representative performance comparisons.
- The workbook does not define the meanings of the Order Priority codes.
- The country revenue summary sheet displays only five country entries; the complete country analysis should use the main Data sheet.

---

## 🚀 Future Improvements

- Perform advanced data cleaning and transformation.
- Build an interactive Power BI dashboard.
- Use SQL for advanced sales data analysis.
- Create automated reports and KPI tracking.
- Perform deeper customer, product, and regional performance analysis.
- Develop predictive sales and revenue forecasting models.

---

## 💡 Conclusion

This project demonstrates how raw retail transaction data can be transformed into meaningful business insights using Microsoft Excel.

Through sales analysis, profitability analysis, regional comparisons, product performance evaluation, and dashboard visualisation, the project provides a structured understanding of retail business performance.

It also demonstrates practical skills in data analysis, data summarisation, business intelligence, data visualisation, and analytical storytelling.

---

## 👩‍💻 Author

**Data Analytics Project**

Repository: `retail-sales-profitability-analysis`

**Skills Demonstrated:** Microsoft Excel | Data Analysis | Pivot Tables | Data Visualisation | Business Intelligence | Git | GitHub
