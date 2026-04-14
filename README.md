# Adidas Sales Performance Dashboard

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)

## Overview

An interactive Excel dashboard built to monitor Adidas U.S. sales performance across 2020–2021. Designed for analysts in the Business Development department who need to track key business indicators — revenue, profit, cost, and unit sales — on a regular reporting cadence without rebuilding reports from scratch each time.

## Business Context

The dataset is the **Adidas Sales Database**, containing transaction-level records with the following fields: Retailer, Retailer ID, Invoice Date, Region, State, City, Product, Price per Unit, Units Sold, Total Sales, Operating Profit, Operating Margin, and Sales Method.

## Key Metrics

| Metric | Value |
|---|---|
| Total Orders | 2,478,861 |
| Revenue | $899,902,125 |
| Total Cost | $567,767,364 (63%) |
| Profit | $332,134,761 (37%) |

## Dashboard Components

- **KPI Summary Bar** — Top-level cards for Orders, Revenue, Cost, and Profit with donut chart indicators for cost/profit split.
- **Revenue & Profit Trend** — Monthly line chart across 2020–2021 to visualize growth trajectory.
- **Method Revenue** — Donut chart breaking revenue by channel: In-store (40%), Outlet (33%), Online (27%).
- **Sale Units & Profit Margin** — Combo chart showing monthly unit sales (bar) alongside profit margin % (line).
- **Product Performance** — Clustered bar chart comparing Revenue and Profit across 6 product categories (Men's/Women's Apparel, Athletic Footwear, Street Footwear).
- **Retailer Breakdown** — Treemap showing revenue contribution by retailer: West Gear ($243M), Foot Locker ($220M), Sports Direct ($182M), Kohl's ($102M), Amazon ($78M), Walmart ($75M).
- **Revenue by State** — Bing-powered geographic map visualizing revenue distribution across all U.S. states.

## Filters & Interactivity

The dashboard includes slicers that dynamically filter all charts simultaneously:

- **Year**: 2020, 2021
- **Region**: Midwest, Northeast, South, Southeast, West
- **Sales Method**: In-store, Online, Outlet

## Tools Used

- Microsoft Excel (PivotTables, PivotCharts, Slicers, Bing Maps chart, dashboard layout)

---

*Data source: Adidas U.S. Sales Dataset · Period: January 2020 – December 2021*
