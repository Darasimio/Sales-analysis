  # Sales Analysis
 This repository contains code and analysis for sales data. The analysis is divided into several sections, and each section is explained below:
 
## Table of Content

- [Introduction](#Introduction)
- [Business Question](#business_Question)
- [About the dataset](#about_the_dataset)
- [Tools](#Tools)
- [Data cleaning and Preparation](#Data_cleaning_and_Preparation)
- [Data analysis](#Data_analysis)
- [Recommendation](#Recommendations)


## Introduction

Sales analysis is a critical process that helps businesses understand their revenue trends, customer behavior, and overall market performance. By examining sales data, companies can identify patterns, measure the effectiveness of their sales strategies, and make data-driven decisions to improve profitability.

This report provides an in-depth analysis of the sales dataset, highlighting key insights, trends, and potential areas for improvement. It covers the methodology used in analyzing the data, key findings from the sales performance metrics, and actionable recommendations to enhance future sales outcomes.

![Dashboard](https://github.com/user-attachments/assets/6af8799f-12f7-4e59-aecf-cb9d2be68245.PNG)

## Business Question
**How can the superstore increase sales and maximize profit across different regions and customer segments?**


### Analystical Question
❓ Which month recorded the highest sales and profit?  
❓ Which region in the USA has the highest potential for customer acquisition?  
❓ What are the best-selling and most profitable products?  
❓ Who are the most valuable customers?


## About the dataset
The dataset used was a hypothesized one, given by our instructor. It contained a total of 1993 records and 20 fields (excluding the row number field). 
Categories in the dataset included: Location, Customer, Customer’s segments, Product Category, Shipping mode
Metrics in the data included: Sales, Profit, Discount

##Tools
Excel - Data Cleaning
Power Query - Data Preparation
Power BI - Data Analysis / Visualization



## Data cleaning and Preparation
The dataset was opened, explored and cleaned in Ms Excel.  The data preparation stage involved a number of steps which included:  

#### Check for missing values 
Filter way applied to each of the fields to check for missing values, no missing values was observed in all column

#### Check for Duplicate value 
Using the duplicate function in the data ribbon of excel, and excluding the row number column, duplicate was checked for and just one was found. Making 1992 unique records.

#### Check for Data type
Each column was changed to it respective data type – text to text, currency (profit, sales) etc

#### Normalization
The data was imported into power bi query for further preparation. It was broken down into segments (normalized), so as to be able to manipulate the data more easily and faster.  Segments such as Customer, Location, Region, Product were created. The different segments were merged as one and inputed into power bi workspace.

#### Modelling
In a Power bi desktop, date table was created in order to have a unified date table to use for the entire analysis.  In the model view, relationship was confirmed and created across the tables. The data model had a star schema relationship.


## Data analysis
#### Overview
A total of 7579 units of goods were sold by th superstore in the year 2014. A total of $483.97k was recovered from sales, and a total of $49.56k was gained as profit by the superstore from sales.\
**The superstore made only 10% of its total sales as profit for the entire year.**

#### Trend analysis: 
The dataset was based on a year, 2014. Trend analysis was done for the 12 months and 4 Quarters of the year. 
A significant sales increase occurred from July to September. A sharp decline was observed from September to October, though sales later rebounded in November and was sustained in December.\
The month with the best sales was September, with a total of 1000 unit sold and $81.77k worth sales Whereas the month the store made the most profit was in November, a total of $9.29k. 18.7% of the year profit. Most of the customers were seen from the cooperate segment, this could be a strategy to restock work equipment before the start of a new year.

#### Product’s performance: 
Office Supplies products category were the most profitable, contributing 45.59% of total profit.  
Customers from the consumer segments were the primary buyers (1,070 out of 1,992 orders).\
Products in the office supply category is observed to be the most profitable to the superstore, this can also be seen its ordering frequency (1217) as compared to technology product (355) and Furniture (355). It has a total of $22.5k sales.  Though products from the Technology category have the highest return on sales, the amount of returns to the store as profit is low. Technology product are also higher in unit price as compared to the other category of product owning to the high sales return in technology despite the low order frequency.\

#### Customer’s Performance: 
The superstore had Most of their Customers from the consumer segment, that is most of the customers bought products for personal use, with a total order number of 1070 and sales amount of $266.1k, as compared to the other customer’s segments, Cooperate (611 units, $128.4k sales) and Home office (311 units, $89.4K sales).


#### Regional Performance:

California had the highest number of purchases, driving top sales. However, New York residents proved more profitable due to higher unit prices of purchased items.
Texas customers generated no profit despite discounts on products purchased.


## Recommendations
By understanding and observing the partern snd trend of the dataset, I will further reecommend the following:\
-	Products purchased by the Consumer goods should be discounted so as to retain customers 
-	More discount should be placed on Technology categorized product in order to boost profit of the store
-	Increase discounts on furniture to boost profitability.
-	 Consider discontinuing sales to Texas and Illinois as they contribute little to no profit.


The dataset is an interesting one and more time will mean more analysis, needed to be done in fields such as shipping mode and discounts, this will also enhance for further unraveling and recommendations based on findings.

[Dataset used - Superstore 2014.xlsx](https://github.com/user-attachments/files/19459786/Superstore.2014.xlsx)

[Oluwadarasimi_Sales assignment new.pdf](https://github.com/user-attachments/files/19459779/Oluwadarasimi_Sales.assignment.new.pdf)

[Dashboard](https://github.com/user-attachments/assets/af24b7fa-79b5-46df-8268-76dab67ea508)

