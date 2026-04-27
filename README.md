# 🛒 Olist Brazilian E-Commerce Sales Dashboard

An interactive **Power BI** dashboard analyzing sales, logistics, and customer behavior data from **Olist** — Brazil's largest e-commerce marketplace.

---

## 📌 Project Overview

This project explores the [Olist Brazilian E-Commerce public dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) to uncover key business insights around revenue trends, regional performance, product categories, payment preferences, and delivery patterns. The report is designed across **three focused pages**, each targeting a distinct analytical dimension.

---

## 📊 Dashboard Pages

### Page 1 — Sales Overview
A high-level snapshot of overall business performance:
- **Total Sales KPI** — 7.2M in revenue across the dataset period
- **Sales by Year (2016–2018)** — clear year-over-year growth trend peaking at 8.7M
- **Top Product Categories** — led by *cama_mesa_banho*, *beleza_saude*, and *esporte_lazer*
- **Top 4 Regions** — São Paulo (SP) leads with 2.6M, followed by RJ (1.1M), MG (0.9M), and RS (0.4M)
- **Top 4 Cities** — São Paulo (0.9M), Rio de Janeiro (0.6M), Belo Horizonte (0.2M), Brasília (0.2M)
- **Payment Modes** — Credit card is the dominant payment method, followed by voucher and boleto

### Page 2 — Sales & Profit Analysis
A deeper analytical view into profitability and segment behavior:
- **Monthly Sales Trend** — line chart revealing seasonal patterns and quarter-wise fluctuations
- **Profit by Region** — West region leads at 24.1K, followed by East (20.1K), Central (19.9K), and South (17.7K)
- **Sales by Product Category** — Technology (226K) tops revenue, ahead of Furniture (199K) and Office Supplies (184K)
- **Customer Segments** — Pie chart breakdown across Consumer, Corporate, and Home Office segments

### Page 3 — Delivery & Payment Detail Table
A granular drill-down table for logistics and payment analysis:
- **Customer State & City** — geographic breakdown of orders
- **Delivery Days** — per-order delivery time across regions
- **Payment Type** — order-level payment method details
- **Total Items Value** — transaction-level revenue data

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Data modeling, DAX measures, and report building |
| **DAX** | Custom calculated measures and KPIs |
| **Power Query** | Data transformation and cleaning |
| **Olist Dataset** | Source data (Kaggle) |

---

## 💡 Key Insights

- **São Paulo** is the dominant sales region, contributing over a third of total revenue
- **Credit card** is the most preferred payment method across Brazilian customers
- Sales showed consistent **year-over-year growth** from 2016 to 2018
- **Bed, bath & beauty** categories outperform electronics in volume-based sales
- The **West region** yields the highest profit margins despite not being the top revenue region

---

## 📁 Project Structure

```
olist-powerbi-dashboard/
│
├── Olist_Dashboard.pbix       # Power BI report file
├── README.md                  # Project documentation
└── screenshots/
    ├── page1_sales_overview.png
    ├── page2_sales_profit.png
    └── page3_delivery_table.png
```

---

## 📂 Dataset

- **Source:** [Kaggle — Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- **Coverage:** 2016–2018 orders made at multiple marketplaces in Brazil
- **Size:** ~100K orders with product, payment, customer, and logistics data

---

## 🚀 Getting Started

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
2. Clone this repository
3. Open `Olist_Dashboard.pbix` in Power BI Desktop
4. Explore and interact with the three dashboard pages

---

