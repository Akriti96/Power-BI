# 🛍️ Shopify Sales Analysis Dashboard

This Power BI project analyzes e-commerce sales data from a Shopify store to uncover trends in revenue, customer behavior, product performance, and seasonal sales patterns.

## 📑 Table of Contents
- [📊 Overview](#-overview)
- [📂 Data Source & ETL](#-data-source--etl)
- [📐 Data Model & Metrics](#-data-model--metrics)
- [📈 Key Insights & Visuals](#-key-insights--visuals)
- [🚀 How to Use](#-how-to-use)
- [📁 Project Structure](#-project-structure)
- [📋 Requirements](#-requirements)
- [📬 Contact](#-contact)

---
## 📊 Overview
This project explores comprehensive sales and customer data from a Shopify store. It provides an end-to-end view of:

- 📈 Transaction performance
- 👥 Customer segmentation
- 🛒 Product-level insights
- 🌍 Regional sales trends
- 💳 Payment method analysis

Designed to help business stakeholders track KPIs, uncover patterns, and support data-driven decisions.
----

## 🛠️ Tools & Technologies

- **Power BI Desktop**  
- **Microsoft Excel** – Data source  
- **DAX** – Measures and KPIs  
- **Power Query** – Data transformation and modeling

## 📂 Data Source

- Format: Excel (.xlsx)
- Tables Used:
  - Orders
  - Products
  - Customers
  - Line Items

Data was cleaned and modeled using Power Query Editor within Power BI.

---

## 📐 Metrics & KPIs

| Metric | Description |
|--------|-------------|
| **Net Sales** | Total revenue from orders |
| **Total Customers** | Count of unique customers |
| **Repeat Rate** | % of returning customers |
| **Life Time Value (LTV)** | Avg. total revenue per customer |
| **Purchase Frequency** | Avg. # of purchases per customer |
| **Average Order Value** | Net Sales ÷ Total Orders |
| **Sales by Product Type** | Total customers by category |
| **Sales by Payment Gateway** | Gateway-based customer distribution |
| **Regional Sales** | City- and province-level customer distribution |

---

## 📈 Key Dashboard Visuals

### 📄 Main Report Page

![Report Screenshot](https://github.com/Akriti96/Power-BI/blob/main/Spoify%20Sales%20Analysis/dashboard.PNG)

- **Transaction Summary KPIs**
- **Customer Funnel (First-time vs Returning)**
- **Time-Series: Customer Sales Trend**
- **Payment Method Analysis (Donut Chart)**
- **Top Products by Customers**
- **Regional Distribution (Map & Bar Chart)**

---

### 🧾 Details Tab

![Details Screenshot](https://github.com/Akriti96/Power-BI/blob/main/Spoify%20Sales%20Analysis/report.png)

- **Order-level breakdown**  
- Shows:
  - Order ID, Customer Name & City  
  - Product Type & Gateway  
  - Quantity, Net Sales, Tax, Total Price USD  
- **Totals Row** summarizing:
  - Number of Orders
  - Total Revenue
  - Cumulative Tax
  - Final Price

---

## 🚀 How to Use

1. Clone/download this repository  
2. Open the file `Shpoify Sales Analysis Report.pbit` in Power BI Desktop  
3. When prompted, load the Excel data source (make sure the data file is in the correct path)  
4. Refresh the dashboard and explore using slicers:
   - Province
   - Gateway
   - Customer Segments
   - Product Categories

---

## 📁 Project Structure

| File | Description |
|------|-------------|
| `Shpoify Sales Analysis Report.pbit` | Power BI template file |
| `Report.PNG` | Screenshot of main dashboard |
| `details screen.PNG` | Screenshot of detailed orders tab |
| `README.md` | Project documentation |

---

## ✅ Requirements

- Power BI Desktop (June 2024 or newer)
- Excel data source matching the schema used in the template
- Basic familiarity with Power BI slicers and interactions

---

## 📬 Contact

Created by **[Akriti](https://github.com/Akriti96)**  
💡 Interested in data analytics, visualization, and e-commerce BI solutions.  
📩 For feedback or collaboration: [GitHub Profile](https://github.com/Akriti96)

---

> **Note:** This dashboard is great for showcasing Power BI skills, especially for job interviews, freelance clients, or portfolio presentations in e-commerce analytics.

