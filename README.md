# pizza-sales-analysis
Analysis of 48,000+ pizza order lines using SQL and an Excel dashboard to find sales trends, peak hours, and top-selling pizzas
# Pizza Sales Analysis | SQL & Excel

## About This Project
A pizza restaurant records thousands of orders, but raw order lines don't show what is selling, when customers order, or which items to promote. This project analyses a full year (2015) of pizza orders to answer those questions, using SQL for the calculations and Excel for an interactive dashboard.

## Questions I Set Out to Answer
- How much revenue did the restaurant make, and what does a typical order look like?
- Which days and hours are the busiest?
- Which pizza categories and sizes bring in the most sales?
- Which pizzas sell best, and which sell worst?

## Data
Pizza sales data for 2015 with **48,620 order lines** and **21,350 orders** Each row has the order date and time, pizza name, category, size, quantity, and price.

## Tools
| Purpose | Tool |
|---|---|
| Calculations and aggregations | SQL |
| Pivot tables, charts, and date slicer | Microsoft Excel |

## Headline Numbers
| Total Revenue | Total Orders | Pizzas Sold | Avg Order Value | Pizzas per Order |
|---|---|---|---|---|
| $817,860 | 21,350 | 49,574 | $38.31 | 2.32 |

## What the Data Shows
**Timing**
- Friday is the busiest day (3,538 orders) and Sunday is the quietest (2,624).
- Orders peak in two windows: around lunch (12 to 2 pm) and early evening (5 to 7 pm).

**Categories and sizes**
- Classic leads on sales (27%) and pizzas sold (14,888), but all four categories sit between 24% and 27% of revenue.
- Large pizzas produce almost half of all revenue (46%), followed by medium (30%) and small (22%). XL and XXL together are under 2%.

**Best and worst sellers**
- Top sellers: The Classic Deluxe Pizza (2,453), The Barbecue Chicken Pizza (2,432), and The Hawaiian Pizza (2,422).
- The Brie Carre Pizza sells the least by a wide margin (490 units), about half of the next-lowest item.

## Suggested Actions
- Staff up for the lunch and early-evening peaks, especially on Fridays.
- Feature the top sellers in promotions and combos.
- Review whether The Brie Carre Pizza should stay on the menu or be reworked.
- Consider dropping or simplifying XL and XXL sizes, which contribute very little.

## Repository Contents
| File | Description |
|---|---|
| `pizza_sales.csv` | Dataset |
| `pizza_sales_queries.sql` | SQL queries for KPIs, trends, category and size shares, and best/worst sellers |
| `pizza_sales_dashboard.xlsx` | Excel dashboard |


## Acknowledgements
Learned the workflow through a guide; SQL queries run and README written by me.
