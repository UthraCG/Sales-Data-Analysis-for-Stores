Aim:

The Challenge - One challenge of modelling retail data is the need to make decisions based on limited history. Holidays and select major events come once a year, and so does the chance to see how strategic decisions impacted the bottom line. In addition, markdowns are known to affect sales – the challenge is to predict which departments will be affected and to what extent.


Process:

 historical sales data for 45 stores located in different regions - each store contains a number of departments. The company also runs several promotional markdown events throughout the year. These markdowns precede prominent holidays, the four largest of which are the Super Bowl, Labor Day, Thanksgiving, and Christmas. The weeks including these holidays are weighted five times higher in the evaluation than non-holiday weeks.

 Stores
Anonymized information about the 45 stores, indicating the type and size of store
Features
Contains additional data related to the store, department, and regional activity for the given dates.
Store - the store number
Date - the week
Temperature - average temperature in the region
Fuel_Price - cost of fuel in the region
MarkDown1-5 - anonymized data related to promotional markdowns. MarkDown data is only available after Nov 2011, and is not available for all stores all the time. Any missing value is marked with an NA
CPI - the consumer price index
Unemployment - the unemployment rate
IsHoliday - whether the week is a special holiday week
Sales
Historical sales data, which covers 2010-02-05 to 2012-11-01. Within this tab you will find the following fields:
Store - the store number
Dept - the department number
Date - the week
Weekly_Sales -  sales for the given department in the given store
IsHoliday - whether the week is a special holiday week

In Stores Data

Store: This is the different types of stores in different area. Type: This is the store where it is located City or Town or small town. Size: This is the total area of the stores.

In Sales Data

Dept: Department is nothing but a different section in a store. Date: The date stores have sales. Weekly_sales: Overall sales including all section in each stores every week. IsHoliday: This is referred as the week is having any holidays in a week or not.

In Features Data

Temperature: The temperature in the particular area where the store is located. Fuel_Price: Cost of the Fuel in the particular area where the store is located. MarkDown1,2,3,4: Unemployment: Rate of unemployment in the particular area where the store is located. CPI: Customer Price Index is nothing but a reduction in the cost from the marked price. Here from the tables sales data and features data finding the overall sales per year for each store and calculating overall estimated sales and efficiency of sales per year for each store.

Result:

All the stores are analyzed with each of there columns and used ML Algorithm to predict thier maximum sales. and the stores to get effective on thier sales.
