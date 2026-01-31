# **Operational KPI reporting in Excel**

## Project Overview

This project demonstrates how operational business KPIs can be calculated, analysed, and presented using advanced Excel techniques without relying on dedicated BI tools.

The goal was to transform raw transactional data into clear, decision-ready dashboard suitable for non-technical stakeholders (operations, sales, management teams).

## Dataset

* Source: Online Retail dataset(Kaggle)
* Type: Transaction-level sales data
* Key fields:

  * InvoiceDate
  * Country
  * CustomerID
  * Product description
  * Quantity
  * Revenue (calculated)

The dataset contains real-world issues such as missing values, inconsistent formatting, and incomplete time periods.

## Tools and Skills Used

* Microsoft Excel

  * Pivot Tables
  * Calculated fields
  * Data cleaning and validation
  * Custom number formatting
  * Charts and dashboard layout
* Business analytics

  * KPI definition
  * Trend analysis
  * Ranking and contribution analysis

## KPI Definitions

The following KPIs were calculated and validated:

* Total Revenue
* Total Orders
* Total Customers
* Average Order Value (AOV)
* Average Items per Order
* Revenue per Customer

All KPIs are derived directly from the cleaned transactional data using Excel formulas and PivotTables.

## Dashboard Structure

#### - KPI Cards

Top-level business metrics shown at the top for quick overview.

screenshots/kpi_cards.png

#### - Revenue Over Time

Monthly revenue trend showing seasonality and changes over time.

* Values shown in £ Millions
* Final month is incomplete (real-world data case)

screenshots/Revenue_over_time.png

#### - Top 10 Countries by Revenue

Shows which countries generate the most revenue.

* Horizontal bar chart
* Values shown in £ Millions
* UK is crearly the main market

screenshots/Top_Countries.png

#### - Top 10 Products by Revenue

Shows the best-selling products by revenue.

* Values shown in £ Thousands
* Sorted from highest to lowest

screenshots/Top_Products.png

#### - Full Dashboard overview

All elements combined into one operational dashboard.
screenshots/Dashboard_overview.png

## Business Insights

* The UK generates most of the revenue, while other countries contribute much smaller amounts.
* Revenue shows strong seasonality, with higher sales at the end of the year.
* A small number of products drive most revenue, which is useful for inventory and sales planning.

## Repository Structure

**excel-kpi-reporting/**

**├── data/**

**│├── raw_data_sample.csv**

**│ └── clean_data_sample.csv**

**│**

**├── screenshots/**

**│ ├── Dashboard_overview.png**

**│ ├── kpi_cards.png**

**│├── Revenue_over_time.png**

**│├── Top_Countries.png**

**│ └── Top_Products.png**

**│**

**└── README.md**

## Key Takeaway

This project reflects real-world Excel reporting where advanced analytics, clean presentation, and business logic matter more than tooling. It demonstrates how Excel can still serve as a poweful BI solution in operational environments.
