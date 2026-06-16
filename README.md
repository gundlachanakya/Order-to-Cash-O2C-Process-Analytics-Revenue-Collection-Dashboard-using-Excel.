# Order-to-Cash-O2C-Process-Analytics-Revenue-Collection-Dashboard-using-Excel.
# 📦 Order-to-Cash (O2C) Data Analysis

A comprehensive Excel-based analytics project tracking the end-to-end Order-to-Cash process across regions, customers, and months — covering revenue, collections, outstanding receivables, and aging analysis for FY 2024–25.

---

## 📊 Project Overview

This project analyzes **1,000 sales transactions** across **4 regions** and **12 months**, providing actionable insights into:

- Revenue generation and regional performance
- Payment collection efficiency
- Outstanding receivables and aging buckets
- Customer-level risk profiling
- Key O2C KPIs (DSO, Collection Efficiency, Fulfillment Rate)

---

## 📁 File Structure

```
O2C_Data_AutoRecovered_.xlsx
│
├── O2C_Data        # Raw transactional data (1000 rows × 15 columns)
├── Pivot           # Pivot tables: Revenue, Monthly Trend, Collections, Aging
├── Dashboard       # Summary KPI dashboard (Total Revenue, Collections, DSO)
└── KPI             # Calculated KPIs (Collection Efficiency, Fulfillment Rate, DSO)
```

---

## 🗂️ Dataset Schema

| Column | Description |
|---|---|
| `OrderID` | Unique order identifier (e.g., O0001) |
| `Customer` | Customer / business name |
| `Region` | Sales region — East, West, North, South |
| `Month` | Month of the order (Jan–Dec) |
| `OrderDate` | Date the order was placed |
| `InvoiceDate` | Date the invoice was raised |
| `DueDate` | Payment due date |
| `PaymentDate` | Actual payment received date |
| `OrderValue` | Total value of the order (₹) |
| `AmountPaid` | Amount collected from the customer (₹) |
| `Status` | Payment status (see below) |
| `Days to Invoice` | Days between order and invoice |
| `CollectionDays` | Days taken to collect payment |
| `Outstanding Amount` | Unpaid balance (₹) |
| `Aging Bucket` | Receivable aging category |

---

## 📌 Order Status Categories

| Status | Count | Description |
|---|---|---|
| Paid | 519 | Fully paid on time |
| Paid Late | 163 | Paid after due date |
| Overdue | 107 | Past due, not yet paid |
| Outstanding | 106 | Pending payment |
| Cancelled | 60 | Order cancelled |
| Partial | 45 | Partially paid |

---

## 📈 Key KPIs (FY 2024–25)

| Metric | Value |
|---|---|
| Total Revenue | ₹27.93M |
| Total Collections | ₹24.33M |
| Outstanding Amount | ₹11.03M |
| Collection Efficiency | 87.1% |
| Average Collection Days | ~110 days |
| Days Sales Outstanding (DSO) | ~144 days |
| Fulfillment Rate | 94.0% |

---

## 🗺️ Regional Coverage

| Region | Orders | Revenue |
|---|---|---|
| West | 623 | ₹22.02M |
| South | 135 | ₹4.87M |
| North | 128 | ₹4.42M |
| East | 114 | ₹4.06M |

---

## 📉 Aging Buckets

| Bucket | Orders |
|---|---|
| 0–30 Days | 555 |
| 31–60 Days | 172 |
| 90+ Days | 273 |

> ⚠️ **27.3% of orders** fall in the 90+ days bucket — flagged for immediate follow-up.

---

## 🛠️ Tools Used

- **Microsoft Excel** — Data storage, Pivot Tables, Dashboard, KPI calculation
- **Python (pandas, matplotlib)** — Data analysis and chart generation
- **ReportLab** — PDF report generation

---

## 📄 Generated Report

A full project report (`O2C_Project_Report.pdf`) is included, covering:

- Executive Summary
- KPI Dashboard
- 6 visual charts (Revenue, Collections, Status, Aging, Customers)
- Regional & Status breakdown tables
- Key findings and recommendations

---

## 🚀 How to Use

1. Open `O2C_Data_AutoRecovered_.xlsx` in Microsoft Excel
2. Navigate to the **Dashboard** or **KPI** sheet for summary metrics
3. Use the **Pivot** sheet to filter and explore trends
4. Refer to `O2C_Project_Report.pdf` for the full written analysis

---

## 👤 Author

> Gundla Chanakya

---
