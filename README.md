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

- **Overall business is profitable** — $2.30M in sales generated $286K profit (12.5% margin) — but **18.7% of all orders (1,869 out of 9,977) lose money**
- **Furniture is the weak link**: despite generating similar revenue to Office Supplies and Technology (~$741K), its profit margin is just **2.5%** vs. 17.4% (Technology) and 17.0% (Office Supplies).
- **Tables are the single biggest problem**: -$17,725 in losses, an **-8.6% margin** — losing money on nearly every sale.
- Bookcases (-$3,473) and Supplies (-$1,189) are also net loss-makers.
- **Discounting above 20% consistently destroys profit**: average profit per order is +$67 at 0% discount, but flips to **-$78 at 20-40% discount** and **-$135 at 40-60% discount**
- **Geographic gap**: Texas (-$25.7K), Ohio (-$17K), and Pennsylvania (-$15.6K) are the worst-performing states by profit, while California (+$76.3K) and New York (+$74K) lead.
- Copiers (37.2% margin), Labels (44.4%), and Envelopes (42.3%) are the most profitable sub-categories relative to their sales.

## Recommendations

- **Cap discounts on Tables and Bookcases at 15% or lower** — current discounting on these sub-categories is actively destroying margin, not just eating into it.
- **Reassess Furniture pricing/cost structure** — the category's 2.5% margin is far below the business average and needs investigation (shipping costs, supplier pricing, or manufacturing overhead).
- **Review discount approval policy above the 20% threshold** — this appears to be the tipping point where profit turns negative across the business.
- **Investigate underperforming states (Texas, Ohio, Pennsylvania)** — determine if losses are driven by product mix, excessive discounting, or regional cost factors.
- **Double down on high-margin sub-categories** (Copiers, Labels, Envelopes, Paper) in marketing and inventory planning.

## Dashboard Preview

*(screenshot or link to be added once Power BI dashboard is complete)*

## Author

Vasanthan — Data Analyst | Career transitioner from Sales & Accounts to Data Analytics
