# Superstore Profitability Analysis

Exploratory data analysis and dashboard project investigating sales and profitability drivers in a retail superstore dataset, with a focus on where the business is losing money and why.

## Problem Statement

The Superstore generates strong overall revenue, but not every sale is profitable. This project investigates:
- Which product categories and sub-categories are profitable vs. loss-making
- How discounting affects profit margins
- Which regions/states underperform despite strong sales
- Actionable recommendations to improve overall profitability

## Dataset

- **Source:** Sample Superstore dataset (retail orders, ~10,000 rows)
- **Fields:** Ship Mode, Segment, Country, City, State, Postal Code, Region, Category, Sub-Category, Sales, Quantity, Discount, Profit
- **File:** `data/SampleSuperstore.csv`

## Tools & Stack

- **Python** (pandas, matplotlib/seaborn) — data cleaning and exploratory analysis
- **Power BI** — interactive dashboard
- **Jupyter Notebook** — analysis workflow

## Project Structure

```
├── data/                 # Raw and cleaned dataset
├── notebooks/            # Python EDA notebook(s)
├── dashboard/            # Power BI file and/or dashboard screenshots
└── README.md
```

## Methodology

1. **Data Cleaning** — removed duplicate records, validated data types, checked for missing values
2. **Exploratory Analysis** — profitability breakdown by Category, Sub-Category, Region, State, and Segment
3. **Discount Impact Analysis** — examined relationship between discount levels and profit
4. **Dashboard** — built an interactive Power BI dashboard for stakeholders to explore the findings

## Key Findings

*(to be updated as analysis progresses)*

- Overall profit is positive, but a meaningful share of orders are loss-making
- Certain sub-categories (e.g. Tables, Bookcases) consistently lose money
- Profit margins decline sharply once discounts exceed ~20%
- Some states show strong sales but negative profit

## Recommendations

*(to be updated as analysis progresses)*

## Dashboard Preview

*(screenshot or link to be added)*

## Author

Vasanthan — Data Analyst | Career transitioner from Sales & Accounts to Data Analytics
