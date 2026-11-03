# E-Commerce Sales vs Target Dashboard (Power BI)

Power BI dashboard that tracks e-commerce sales against category targets and highlights monthly trends and sub-category profitability.

## Dataset
Three related tables: **List of Orders** (order date, customer, state, city), **Order Details** (amount, profit, quantity, category, sub-category) and **Sales Target** (monthly targets by category).

## What I did
**1. Data preparation (Power Query)** – `Sales_Data_Preparation_PowerQuery.pbix`
- Removed duplicates and blank rows, fixed data types and capitalisation
- Merged orders with order details; added Profit Margin and Profit Status (loss / profit) columns
- Grouped targets by category and by month; built table relationships

**2. Dashboard (DAX + visuals)** – `Sales_vs_Target_Dashboard.pbix`
- DAX measures: Total Sales, Total Profit, Profit Margin, YTD Sales, Order Count
- Calculated columns: Category Type, Revenue per Order, Above / Below Average Sales
- Visuals: sales vs target by category, monthly sales trend, profit margin by sub-category, profit vs quantity scatter, sales by city map, sub-category treemap, state-wise order funnel, state slicer

## Files
| File | Description |
|------|-------------|
| `Sales_vs_Target_Dashboard.pbix` | Final dashboard |
| `Sales_Data_Preparation_PowerQuery.pbix` | Data cleaning and merging in Power Query |

*Open `.pbix` files in Power BI Desktop (free).*

## Tools
Power BI · Power Query · DAX · Data Modelling

---
*Fabeena Fasal* · [LinkedIn](https://www.linkedin.com/in/fabeena-fasal)
