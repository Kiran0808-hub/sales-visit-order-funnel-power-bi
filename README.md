# sales-visit-order-funnel-power-bi
Power BI Sales Visit &amp; Order Funnel Dashboard analyzing field visits, order intent, conversion rates, trends, field executive performance, and data quality.
# Sales Visit & Order Funnel Analysis – Power BI

## Project Overview

This project demonstrates a Power BI dashboard developed to analyze sales visits, order intent, and conversion from field visits to ready-to-order shops.

## Objectives

- Clean and standardize sales visit data
- Consolidate status values into meaningful funnel stages
- Analyze order intent and ready-to-order conversion
- Identify visit patterns, trends, and common outcomes
- Review data quality issues
- Build an interactive Power BI dashboard

## Funnel Logic

The main funnel was designed using the following logic:

- Order Intent:
  - Interested and Will Place the Order
  - Order on Call

- Ready to Order:
  - Yes

- Not Interested:
  - No

- Other / Unknown:
  - Other or blank responses

Other responses such as Price Issue, Come Later, Old Stock Available, and Shop Owner Not Available were retained as visit outcomes/reasons rather than being forced into the main funnel.

## Key Analysis

The dashboard includes:

- Total Visits
- Order Intent Shops
- Ready to Order Shops
- Overall Ready-to-Order Conversion
- Order Conversion Funnel
- Field Executive Analysis
- Visit Trend Over Time
- Visit Outcome / Reason Analysis
- Data Quality Review

## Data Cleaning

The data was cleaned by:

- Removing unnecessary formatting inconsistencies
- Trimming and cleaning text values
- Standardizing status values
- Consolidating equivalent responses
- Reviewing incomplete and inconsistent records

## Conversion Metrics

- Order Intent Conversion % = Order Intent Shops / Total Visits
- Ready-to-Order Conversion % = Ready to Order Shops / Order Intent Shops
- Overall Ready Conversion % = Ready to Order Shops / Total Visits

## Data Quality

Records were reviewed for:

- Missing key fields
- Duplicate records
- Inconsistent status values

Data quality issues can affect visit counts and conversion calculations.

## Business Insights

- The funnel shows the progression from order intent to ready-to-order.
- Conversion varies across field executives.
- Visit outcomes highlight common barriers and follow-up opportunities.
- Visit activity varies over time.
- Data quality should be considered when interpreting conversion metrics.

## Tools Used
- Python Libraris
- Power BI
- Power Query
- DAX
- Data Cleaning
- Data Visualization
- - Excel

## Note

This repository contains a portfolio representation of the analysis. Original business/client data has not been publicly shared due to confidentiality considerations.
