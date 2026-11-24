# Pizza Sales Dashboard - Power BI

I built this dashboard to answer a simple question: which pizzas actually make money, and when do people order the most?

I used a dataset of 21,350 orders from a pizza place and cleaned it in Power Query, then built the visuals and DAX measures in Power BI.

## What I found

- Total revenue was **$817.86K** from **49,559 pizzas sold**
- Average order was **$38.31**
- **The Classic Deluxe Pizza** was the clear winner, it made the most money and sold the most
- **The Brie Carre Pizza** was at the bottom, lowest sales and lowest revenue
- **Friday** was the busiest day, and **12 PM** was the peak hour. Basically everyone orders pizza at lunch on Friday.
- Classic pizzas overall beat every other category in both quantity and revenue.

So if I owned this place, I would push Classic Deluxe more on Fridays around noon, and I would probably remove Brie Carre or change its price.

## Dashboard

### Page 1 - Overview
Total revenue, orders, pizzas sold, orders by weekday, orders by hour, and sales by category and size.

![Home](pizza%20home.png)

### Page 2 - Best & Worst Sellers
Top 5 and bottom 5 pizzas by revenue, quantity, and total orders.

![Best and Worst](Best%20and%20worst%20sellers.png)

## Tools I used
Power BI, DAX, Power Query, Excel

## Files in this repo
- `pizza_Sales.pbix` - the full Power BI file
- `pizza_sales_excel_file.xlsx` - the cleaned data I used
