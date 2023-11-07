# Sustainable Premium Fashion Brand Analytics

## Overview

This repository contains SQL scripts and analyses for a sustainable premium fashion brand's customer segmentation project. 
The objective is to leverage customer profitability and demographic data to identify the most receptive, loyal, and profitable clients. 
The brand also aims to understand the performance of their ad creatives on Facebook and Instagram, and analyze consumer purchasing behavior over the past 12 months.

## Objectives

- Segment customers based on profitability and demographics.
- Evaluate the responsiveness of different customer segments to ad creatives (A/ B Tests).
- Analyze purchasing behavior and detect trends.
- Track ad performance on Facebook and Instagram using key metrics.

##  Database Schema

Datasets available for our analysis:

- customers - Contains customer demographic data.
- transactions - Contains records of customer purchases.
- ad_metrics - Contains performance data from Facebook and Instagram ads.

Schema:

**customers:**
- customer_id (Primary Key)
- age
- gender
- location
- join_date

**transactions:**
- transaction_id (Primary Key)
- customer_id (Foreign Key)
- purchase_amount
- purchase_date
  
**ad_metrics:**
- ad_id (Primary Key)
- platform (Facebook or Instagram)
- impressions
- clicks
- total_spend
- conversions
- ad_start_date
- ad_end_date


## Key Performance Indicators (KPIs)
The following KPIs are crucial for the analysis:

1. **Cost per Click (CPC)**
2. **Click-Through-Rate (CTR)**
3. **Cost Per Action (CPA)**
4. **Cost Per Mille (CPM)**
5. **Return On Ad Spend (ROAS)**
6. **Share of Voice**
7. **Conversion Rate**
8. **Cost per Result**
9. **Engagement Rate**
10. **Spend**

## SQL Analysis
The `analysis' file contains advanced SQL queries utilizing CTEs, window functions, and other complex SQL features. 
Each query is documented to explain the logic and the objective it serves.


