# Datavisulization_exam


Q1. Create a sample table in postgres/mysql with following columns (15 Marks)
Table Name : cdac_power_bi
Column
Name - varchar
Id- integer
Age- integer
Dob - date
Insert 5 dummy rows into it and then connect to superset and populate
1. Table Chart
2. Card chart showing max age

Q2.On product_table data set do the following (25 Marks)
● Create table chart with title , vendor,customer name,quantity,price,city
● Add new calculated column naming total_sales which is derived from quantity * price
● Add new measure naming max_price to get max of price column and then display every
vendor max price in table chart
● Create pie chart showing the value and percentage of quantity by vendors
● Create one more column naming total_sales_2022 which is derived from quantity *
price * 1.16
● Create clustered column chart showing both total_sales and total_sales_2022
● Create a slicer chart of price
● Calculate avg sales and show in tile ● Create gauge chart with
○ value as total_sales
○ Maximum value as max of total_sales_2022
○ Target Value as average of total_sales
