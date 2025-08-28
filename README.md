# Sales-Performance-Analysis-2013-2014-
This  projet analyzes sales performance across different segment, states, products and discount bands from 2013-2014. The goal is to help management understand revenue drivers,  profitability and discount impact and to identify areas for business growth.
Business Questions Answered
1.	Which segment contributes the most to total sales and profit?
2.	Which state generates the highest revenue and profitability?
3.	Which products are the top performing in terms of sales and profit?
4.	What is the sales trend over time (monthly)?
5.	How do discount bands affect sales volume and profitability?

## Data Model:
Sales Project: (Unit sold, sales, Profit, COGS, Discounts…)
Dimensions: 
DimProduct (ProductKey, Product, , Name, Manufacturer price, sales price)
DimSegment: (SegmentKey, Segment Name)
DimState: (StateKey, State Name)
DimDiscountBand: (DiscountBandKey, Discount Band)
DimDate: (DateKey, Date,Month,Year,Month Name, Quarter)

## KPI Created
Total Sales
Total Profit
Unit Sold
Average Sales Per Unit

## Key Insights
•	Segment Analysis: Government drove more sales and have higher profits.
•	Geography: Ibadan was the top performing generating 18.46% in sales with a profit of 2.21% while lagos coming second with sales of 15.45% and a higher profit of 2.71%
•	Products: Paseo and VTT were best selling products.
•	Discount impact: High discount bands increase Unit sold but significantly reduced profit, while middle disband has unit sold a little bit lesser than high discount band but has more profit.
•	Time Trends: Sales in 2014 grew compared to 2013, showing steady market expansion.
•	Profitability: Higher sales and profit in  discounted products compare to non-discounted products.

## Tools Used:
Excel: Data Cleaning
Power Bi: Modeling and Visualization
DAX and Power Query.
