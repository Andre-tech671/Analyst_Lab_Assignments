# ShopSmart Retail Analytics & AI Implementation Project

## AnalystLab Africa Experience Lab — Week 1 Assignment

**Mission 01:** Retail Sales Analysis with Microsoft Excel

**Client:** ShopSmart Retail Ltd

**Analyst:** Andre Philip Nyanjahia

**Submission Date:** October 2026

---

## Project Overview

ShopSmart Retail Ltd operates multiple retail stores across Nigeria, selling thousands of products across different categories to thousands of customers monthly. Management identified three critical business challenges:

1. **Sales fluctuations** across stores and regions
2. **Inventory shortages** in certain locations
3. **Increasing product returns**

This project delivers a comprehensive retail sales analysis using Microsoft Excel, including data cleaning, KPI calculation, pivot tables, interactive dashboards, and actionable business recommendations.

---

## Business Objectives

- Clean and prepare 10 interconnected retail datasets
- Build an executive dashboard with KPI cards and interactive slicers
- Identify top-performing products, stores, categories, and regions
- Analyze return patterns and inventory distribution
- Deliver data-driven business recommendations

---

## Datasets Used

| Dataset | Description | Primary Key |
|---------|-------------|-------------|
| Customers | Customer profiles and demographics | Customer_ID |
| Orders | Transaction headers | Order_ID |
| Order Items | Line-item details per order | Order_Item_ID |
| Products | Product catalog | Product_ID |
| Stores | Retail store locations | Store_ID |
| Employees | Staff records | Employee_ID |
| Inventory | Stock levels per store | Inventory_ID |
| Returns | Product return logs | Return_ID |
| Suppliers | Vendor information | Supplier_ID |
| Data Dictionary | Field definitions | — |

---

## Tools & Technologies

- **Microsoft Excel** — Data cleaning, formulas, pivot tables, dashboard
- **Microsoft Access** — Relational database design and ER diagram
- **GitHub** — Version control and portfolio hosting

### Excel Features Used

- Excel Tables (`Ctrl + T`)
- XLOOKUP / VLOOKUP
- Pivot Tables & Pivot Charts
- Slicers & Timeline filters
- Conditional Formatting
- Data Validation
- KPI Cards

---

## Key Performance Indicators (KPIs)

| KPI | Value |
|-----|-------|
| Total Revenue | $7,575,250,086.00 |
| Total Orders | 50,000 |
| Total Customers | 369 |
| Average Order Value (AOV) | $151,505.00 |
| Return / Cancellation Rate | 33.72% |

---

## Dashboard Preview

![Executive Dashboard](dashboard/dashboard_screenshot.png)

### Dashboard Features

- **KPI Cards:** Total Revenue, Total Orders, Total Customers, AOV, Return Rate
- **Charts:**
  - Monthly Sales Trend
  - Revenue by Category
  - Revenue by Store
  - Top Products
  - Sales by State
  - Return Rate by Category
- **Interactive Slicers:** Store, Category, Customer Segment, State

---

## Key Findings

### 1. Revenue Concentration in Beauty & Urban Hubs
- **Beauty** is the top revenue category at **$476.79M**
- **Fashion** follows at **$392.24M**
- Top regions: **Kano State ($274.22M)** and **Abuja FCT ($235.02M)**
- Top store: **ShopSmart Lagos ($301M)**

### 2. High Product Return & Cancellation Rate
- Overall cancellation/return rate: **33.72%**
- Highest friction: **Electronics and Fashion**
- Primary drivers: sizing mismatches and technical return requests

### 3. Supplier Dependency & Inventory Disparities
- Top supplier: **Wilson (310 products)**
- Second: **Johnson (277 products)**
- Low inventory stores: **Enugu, Awka, Asaba**
- High surplus: Tier-1 urban stores

---

## Business Recommendations

### 1. Optimize Inventory Allocation for Regional Outlets
Rebalance logistics and stock levels from high-surplus warehouses to regional branches (Enugu, Asaba, Awka) to prevent stockouts during peak retail cycles.

### 2. Implement Targeted Quality & Sizing Assurance
Investigate the root causes of the **33.72% return rate**, particularly within Fashion and Electronics, by:
- Enhancing product description accuracy
- Strengthening quality control checks
- Reviewing return-window guidelines

### 3. Expand Marketing & Stock Depth in Top Categories
Allocate capital expenditure and promotional campaigns toward:
- High-performing categories: **Beauty and Fashion**
- High-margin **Gold membership** customer tiers

---

## Risk Identified

**Supply Chain & Fulfillment Vulnerability**  
Heavy reliance on unassigned/external distribution pipelines, combined with localized stock depletion in regional stores, exposes ShopSmart to supply shocks, stockouts, and margin erosion from high cancellation rates.

---

## Opportunity Identified

**Digital Public Infrastructure & Data Telemetry Expansion**  
Leverage real-time data analytics and automated inventory tracking across regional branches to capture untapped market share in Kano and Abuja, converting high-traffic browsing into finalized, non-cancelled sales.

---

## Project Structure

```text
ShopSmart-Retail-Analytics/
│
├── README.md
├── LICENSE
├── .gitignore
│
├── data/
│   ├── raw/                        # Original CSV files
│   └── cleaned/                    # Cleaned datasets
│
├── excel/
│   └── ShopSmart_Analysis.xlsx       # Main Excel workbook
│
├── reports/
│   ├── ShopSmart_Executive_Business_Report.pdf
│   ├── ShopSmart_Executive_Business_Report.docx
│   ├── Andre_Philip_Nyanjahia_Executive_Dashboard.pdf
│   ├── Andre_Philip_Nyanjahia_Part 8_Business Questions.pdf
│   └── Andre_Philip_Nyanjahia_PART_1_Data_Understanding.pdf
│
├── dashboard/
│   └── dashboard_screenshot.png
│
└── docs/
    └── data_dictionary_notes.md
