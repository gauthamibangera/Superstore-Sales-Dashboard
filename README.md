# Superstore-Sales-Dashboard
# Superstore Sales Analysis & Dashboard (Excel)

Interactive Excel dashboard analysing 9,994 sales records to examine sales trends, profitability, customer segments and shipping performance.



## Business questions
- How do sales change over the year, and when are the peak months?
- Which sub-categories and products make or lose money?
- Which customer segments and regions drive sales and profit?
- How long do orders take to ship for each ship mode?

## Data
Superstore Sales dataset from Kaggle (9,994 rows, 5,009 orders).

## What I did
- Fixed inconsistent date formats (Text to Columns).
- Added profit Margin, Days to Ship (Ship Date minus Order Date) and Year columns.
- Built pivot tables and pivot charts, KPI cards, and Year and Region slicers.
- Wrote insights and recommendations from the results.

## Key insights
- Sales are strongest in September, November and December (November peaks at about $350K) and weakest in January and February.
- Tables, Bookcases and Supplies lose money, with Tables the biggest loss.
- Consumer is the largest segment in both sales and profit.
- Standard Class takes about 5 days to ship, vs. 3 for Second Class and 2 for First Class.

## Recommendations
- Consider targeted promotions in January and February.
- Evaluate pricing, discounts and costs for loss-making sub-categories.

## Notes
- Days to Ship measures order date to ship date (the data has no delivery date).
- KPI cards show overall figures and do not change with the slicers.
- Total Orders uses the UNIQUE function, which needs Excel 2021 or Microsoft 365.

## Tools
Microsoft Excel, PivotTables, PivotCharts, Slicers, Excel Functions
