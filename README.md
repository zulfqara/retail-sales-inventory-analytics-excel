# Retail Performance & Inventory Forecasting Dashboard

## Objective:
To analyze the retail store inventory dataset from 2022–2023 in order to derive insights into product demand, units sold, revenue, and inventory levels, and to evaluate the impact of promotions on overall revenue performance.

## Problem Statement
The retail store aims to conduct a detailed analysis of product-level performance across its stores, focusing on revenue, demand, inventory levels, and units sold. By comparing demand, inventory, and units sold, the analysis seeks to identify instances of overstocking and stock shortages. The primary objective is to optimize inventory management, minimize overstocking and understocking, and enable data-driven actions for products with low revenue contribution.

## Dashboard Overview

 **Revenue Comparison**:
  Demonstrating the comparison of product revenue using Column Bar applying interactive filters. Overall, grocery products generated the highest revenue, followed by       furniture, while the toys category recorded the lowest revenue.
  
**Inventory Health**:
  Visualising the compares between demand, units sold, and inventory levels for each product using combo charts units sold and inventory as column bar and demand as a line     to identify stock imbalances and inventory management issues.
  
**Prices**:
  Displays a table showing the entry-level and premium pricing of products.

## Methodology:
I used Excel Power query to fetch, transform and load the dataset into the excel to complete the analysis. Here are the steps I took:

1. **Data Cleaning:** I fixed the region names and date formats so the data was consistent.
2. **Pivot Tables:** I used Pivot Tables to summarize large amounts of data into simple totals like "Total Revenue" and "Average Inventory."
3. **Analysis:** I compared the "Demand" (what we thought we would sell) against "Units Sold" (what we actually sold) to find errors in the forecast.
4. **Charts:** I created a Combo Chart to visually compare the Inventory bars against the Demand line.
5. **Dashboard:** I added Slicers for Region, Year, and Month so users can filter the data easily.

## Insights:
**Total Revenue**: A total revenue of 397M was generated from 2022–2023, with an average sales price of 61.

**Promotion Impact**: Promotions contributed to 65% of total revenue, indicating that discounted pricing significantly influenced customer purchasing behavior.

**Growth**: Revenue growth in 2023 declined by 2.5 compared to 2022.

**Top Performers**: Grocery and furniture products contributed 37% of the total revenue across 2022 and 2023.

**Overstocking**: Products were excessively overstocked in both years, with grocery items showing particularly high inventory levels.
* **Excessive Grocery Stock:** Groceries make the most revenue ($147M) of the total, but we are holding 3 times more stock than we need. This costs the company extra money to store.
* **Forecast Error:** Persistent overforecasting of sales demand caused the automated ordering system to trigger unnecessary inventory replenishment.
* **Electronics are Efficient:** Unlike groceries, the Electronics category has a healthy balance between stock levels and actual sales.

## Recommendations
1. **Fix the Forecast:** Update the sales prediction numbers to match what is actually selling, rather than hoping for high growth that isn't happening.
2. **Clear Out Stock:** Run sales or promotions on the extra grocery items to free up warehouse space.
3. **Focus on What Works:** Shift budget towards categories like Electronics and Clothing that are selling efficiently.
