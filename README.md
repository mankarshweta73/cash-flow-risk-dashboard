# Municipal Cash Flow Risk Dashboard

## Problem
The National Treasury of South Africa needed to prioritize audit review across 257 municipalities.

## Tools
SQL (aggregation), Python (data cleaning), Power BI (visualization).

## Data
21,141 municipal cash flow transactions from the National Treasury of South Africa (2025–2026).

## Analysis
Grouped transactions by municipality and category. Calculated Finance charges as a percentage of operating cash flow. Identified outliers using a scatter chart.

## Key Finding
Finance charges account for 0.56% of operating cash flow nationally. Kopanong has the highest finance charge ratio. City of Johannesburg and City of eThekwini have the largest absolute exposures.

## Recommendation
Prioritize audit review of the top 5 municipalities by finance charge exposure.

## Files
- `cash_flow_cleaned.csv` — Cleaned dataset
- `Cash_Flow_Dashboard.pbix` — Power BI dashboard
- Summary CSVs — Aggregated query outputs
