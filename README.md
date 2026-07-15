# Customer Analytics in Excel

## Project Overview

This project complements the **NAVA Business Intelligence Solution** by providing an end-to-end customer analytics workflow developed entirely in Microsoft Excel.

The analysis focuses on customer acquisition, purchasing behaviour, customer value and retention through three complementary perspectives:

- Customer Health Analysis
- RFM Segmentation
- Cohort Analysis

Rather than presenting dashboards only, this repository also documents the complete analytical methodology through dedicated workpapers, demonstrating how each business metric was calculated and validated.

---

## Business Objectives

This analysis aims to answer the following business questions:

- How is the customer base evolving over time?
- Which customers generate the highest business value?
- Which customer segments require retention actions?
- When does customer attrition occur?
- How does customer retention evolve across acquisition cohorts?

---

## Repository Structure

```
Customer_Analytics_Excel
│
├── Customer_Analytics_Dashboard.xlsx
│
├── Customer_Analytics_KPI_Workpaper.xlsx
│
├── Customer_Analytics_RFM_Workpaper.xlsx
│
├── Customer_Analytics_Cohort_Workpaper.xlsx
│
├── dashboard_previews
│      ├── customer_health_dashboard.png
│      ├── rfm_dashboard.png
│      └── cohort_dashboard.png
│
└── README.md
```

---

# Dashboard Workbook

The dashboard workbook contains the final executive dashboards prepared for business stakeholders.

Included dashboards:

- Customer Health Dashboard
- RFM Dashboard
- Cohort Analysis Dashboard

The dashboards present business insights without exposing the underlying calculations.

---

# Workpapers

Each workpaper documents the analytical process used to produce the dashboards.

## KPI Workpaper

Documents:

- Customer KPI calculations
- Validation methodology
- Business interpretations
- Executive metrics

---

## RFM Analysis Workpaper

Documents:

- Customer aggregation
- RFM score calculation
- Customer segmentation
- Revenue distribution by segment
- Business conclusions

---

## Cohort Analysis Workpaper

Documents:

- Customer acquisition cohorts
- Retention calculations
- Cohort matrices
- Heatmap construction
- Retention insights

---

# Excel Techniques

The project demonstrates advanced Excel techniques including:

- Pivot Tables
- Dynamic formulas
- FILTER
- UNIQUE
- COUNTIFS
- SUMIFS
- XLOOKUP
- Conditional Formatting
- Heatmaps
- Interactive dashboards
- Business KPI design

---

# Key Business Insights

### Customer Health

- Customer acquisition increased significantly year-over-year.
- Nearly half of customers purchase only once.
- Customer Lifetime Value declined despite revenue growth.

### RFM Analysis

- Customer value is concentrated among Champions and Loyal Customers.
- More than one-third of customers are classified as Lost Customers.
- Growth Opportunities represent the largest segment for future value creation.

### Cohort Analysis

- Only 18% of newly acquired customers place another order in the following quarter.
- Customer attrition is concentrated immediately after acquisition.
- Customers retained beyond the first year demonstrate stronger long-term loyalty.

---

# Project Methodology

This repository follows the same analytical approach used throughout the NAVA Business Intelligence portfolio.

```
Raw Sales Data
        │
        ▼
Customer Aggregation
        │
        ▼
Business KPI Calculations
        │
        ├──────────► Customer Health Dashboard
        │
        ├──────────► RFM Analysis
        │
        └──────────► Cohort Analysis
```

Each analytical step is fully documented through dedicated workpapers to ensure transparency, reproducibility and auditability.

---

# About this Project

This repository was developed as part of the **NAVA Business Intelligence Portfolio** to demonstrate advanced customer analytics capabilities using Microsoft Excel.

The project combines business analysis, customer segmentation and retention analytics while following a structured, workpaper-based approach inspired by audit and consulting methodologies.
