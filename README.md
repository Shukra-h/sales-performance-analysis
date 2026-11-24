# Sales Performance & Business Intelligence Analytics

An end-to-end sales analytics project demonstrating data cleaning, spreadsheet analysis, DAX modelling, and interactive business intelligence reporting using Microsoft Excel, Google Sheets, and Power BI.

## Project Overview

The objective was to transform a raw sales dataset into actionable business insights by answering five stakeholder questions covering overall sales performance, channel contribution, product performance, pending orders, and refund behaviour.

## Tools & Technologies

- Microsoft Excel
- Google Sheets
- Power Query
- Power BI
- DAX

## Project Workflow

### 1. Data Cleaning & Preparation
- Inspected and cleaned the raw sales dataset.
- Prepared calculated columns and enriched records using lookup functions.
- Applied spreadsheet formulas including XLOOKUP, UNIQUE, SUMIFS, COUNTIFS, and ARRAYFORMULA.
- Standardised data types and date formats.

### 2. Excel Analysis
- Analysed paid and pending order values.
- Evaluated sales performance by month and channel.
- Compared product performance by paid units and order value.
- Calculated channel-level snapshot refund rates.
- Used PivotTables and formulas to validate results.

### 3. Power BI Development
- Imported and transformed the cleaned dataset using Power Query.
- Developed DAX measures for business KPIs.
- Built a two-page interactive dashboard.
- Implemented synchronised Month and Channel slicers.
- Created KPI cards, trend charts, product comparisons, and operational summaries.

## Key Findings

- Total Paid Order Value: ₦1,610,000.
- Paid Orders: 55.
- Average Paid Order Value: ₦29,272.73.
- Website contributed 35.81% of Paid Order Value.
- Pending Order Value: ₦346,500.
- Mouse led paid units with 33 units.
- Headset generated the highest product Paid Order Value at ₦472,000.
- WhatsApp recorded the highest snapshot refund rate at 25%.

## Dashboard Preview

See the screenshots in the `screenshots/` directory.

## Business Questions

1. What is the total and monthly Paid Order Value?
2. Which channel contributes the most Paid Order Value?
3. Which products lead by paid units and order value?
4. How much order value remains Pending, and where is it concentrated?
5. Which channel has the highest snapshot refund rate?

## Definitions

- Order Value = Quantity × Unit Price − Order Discount.
- Paid Order Value includes Paid orders only.
- Pending Order Value includes Pending orders only.
- Average Paid Order Value = Paid Order Value ÷ Paid Orders.
- Snapshot Refund Rate = Refunded Orders ÷ (Paid Orders + Refunded Orders).

Pending and Failed orders are excluded from the refund-rate denominator.

## Disclaimer

This project uses a sample sales dataset for educational and portfolio demonstration purposes. The reported findings are descriptive and should not be interpreted as conclusions about a real business.
