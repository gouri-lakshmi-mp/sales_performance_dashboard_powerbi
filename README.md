# Sales Performance Dashboard (Power BI)

A two-page interactive Power BI dashboard that analyses retail sales to show which categories, regions, segments, products and customers drive revenue.

## Business Questions
- Which categories, regions and segments generate the most sales?
- How have sales changed from 2015 to 2018?
- Who are the top products, customers and states?

## Dataset
Superstore sales dataset from Kaggle (`train.csv`). It contains sales values only, with no profit, cost or discount columns, so profitability analysis is outside the scope of this project.

## Tools Used
Power BI (Power Query, DAX), Excel

## Key Metrics
| Total Sales | Total Orders | Total Customers | Avg Order Value |
|---|---|---|---|
| 2.26M | 4,922 | 793 | 459.48 |

## Dashboard Pages
1. **Sales Dashboard:** KPI cards, sales by category, sub-category, region and year, with region and segment filters.
2. **Products and Customers:** top products, top customers, sales by segment, orders by ship mode, and top states.

## Key Insights
1. **Consumer** is the largest segment at 50.76% of sales (1.15M), followed by Corporate at 30.44% (0.69M) and Home Office at 18.79% (0.42M).
2. **Technology** is the top-selling category, followed by Furniture and Office Supplies.
3. **Phones** and **Chairs** are the best-selling sub-categories.
4. **West** and **East** are the strongest regions, and **South** is the weakest.
5. Sales dipped slightly in 2016, then grew every year to roughly 0.7M in 2018.
6. **California** and **New York** lead state sales, and **Standard Class** is the most used shipping mode.

## Recommendations
- Keep the focus on the Consumer segment, and grow Corporate and Home Office sales.
- Study what drives sales in West and East and apply it to the South region.
- Promote the top sub-categories, Phones and Chairs, to build on strong demand.

## Dashboard Preview


![Sales Dashboard](images/page1.png)




![Products and Customers](images/page2.png)



## Repository Contents
- `dashboard/sales_dashboard.pbix`: the Power BI file
- `data/train.csv`: the dataset
- `images/`: dashboard screenshots

## Limitations
The dataset has no profit or cost data, so this analysis covers sales performance only.


