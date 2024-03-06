# AdventureWorks-2022-Customer-and-Sales-Analysis
## Introduction
![](salespic)
----
This project was given during my study in the School of Data at Axia Africa. The aim is to analyze customer spending habits and derive insights for targeted marketing strategies.

## Business Question
### Project description
Axia Africa wants to identify:
1.	The top 10 and least 10 selling products.
2.	Retrieve customer demographic information.
3.	Determine the average order value and total revenue. 

## Data Source
The data provided is the AdventureWorks 2022 database. To retrieve the dataset, I had to use SQL queries to join relevant tables, sort, and filter.
![](customernew)
![](salesnew)

The first query retrieved data from the Customer and Sales Territory tables, providing customer demographic information. 
The second query retrieved data from the Product, Sales Order Detail, and Order Header tables. These provide insights on the top selling, least selling, and average order value, and total revenue generated from orders.

## Skills Demonstrated
•	DAX with Power BI
•	SQL 
•	Data visualization with Power BI

## Data Cleaning
While carrying out EDA on the retrieved dataset, I noticed that the data was clean.
## Statistical Analysis
1.	To calculate for **total revenue**, I added a column to the sales table and use the DAX to multiply the **OrderQty** and **UnitPrice** columns.
2.	To calculate for **Average Order Value**, I created a measure for the count of the OrderQty column. This measure was named the ‘number of orders. Then, I used DAX division formular to divide the total revenue by the number of orders. This was done in another measure which was named ‘Average Order Value’.

## Data Visualization
The report is a 2-page visual connected by an arrow-shaped page navigator at the top left and right sides respectively.
![](project1_customer)
![](project1sales)
---------
### The Customer Demographic Report
The KPI include:
•	Total customers; which are 20,000
•	Total territories; which are 10
•	Total countries; which are 6
•	Total continents which are 3.
The report also shows that North America is the continent with the most customers, with 4,696 being in the Southwest region and 43.58% of them being in the U.S.

### The Sales Report
The KPI include:
•	Total revenue at $100.37M
•	Average Order Value at $909.80
•	Number of orders at 121,000
•	Total quantity ordered at 275,000
The report also shows that CA-1098 is the top product sold by order quantity while FR-T67U-58 is the least product sold by order quantity.
You can interact with both dashboard here https://app.powerbi.com/groups/me/reports/f6a5509d-9a3f-45d3-a3ab-83c686f1c8e1/ReportSection?experience=power-bi

## Conclusion and Recommendation
Customers spend an average of $909.80 on orders with Product CA-1098 being most ordered. This means that more effort should be made to maintain the stock quantity of the top 10 products in favor of the least selling product. Assessment should also be made on the revenue generated from the product on each group.
Most of the business’ customers are found in North America. This means that while marketing efforts should be focus on maintaining the client base in this region, the business can also explore increasing its reach in other potential regions like the Europe.

