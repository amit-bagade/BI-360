Business Insights 365
=

Project Overview
AtliQ Hardware is growing rapidly in the recent years, and they have decided to implement the data analytics using PowerBi in their company for the first time to surpass their competitors in the market and to make data driven decisions. This project is hoped to give answers to the questions of stakeholder in terms all the aspects like 

Home View,
![Thumbnai 1](https://github.com/amit-bagade/BI-360/assets/160107089/93ddd352-06b1-4551-aba3-1cdfb954d1a6)

Finance View 
![Finance View](https://github.com/amit-bagade/BI-360/assets/160107089/a5f4f774-2072-4780-938c-cc2365263c85)

 Sales View , 
![sales View](https://github.com/amit-bagade/BI-360/assets/160107089/bf123446-a7d9-4fd4-9a71-03b0234f4613)

Supply CHain View
![supply chain _  View](https://github.com/amit-bagade/BI-360/assets/160107089/144142c0-fef8-4a16-85a5-4c310b6e9f9b)

Marketing View
![marketing View](https://github.com/amit-bagade/BI-360/assets/160107089/61637ce8-b1fd-4d9d-ad93-b4bebf842264)


Tech stacks

SQL

PowerBi Desktop

Excel

DAX language

DAX studio (for optimizing the report)

Project charter file

PowerBI techniques Learnt

What are all the questions should be asked before staring the project

Creating calculated columns

creating measure using DAX language

Data modeling

Using Bookmarks to switch between two visuals

Page navigation with buttons

Using divide function to prevent zero division errors

creating date table using m language

Dynamic titles based on the applied filters

Using KPI indicators

Conditional formatting the values in visuals using icons or background color

Data validation techniques

PowerBi services

Publishing reports to PowerBi services

Setting up personal gateway to set up the auto refresh of data

PowerBi App creation
Collaboration, workspace, access permissions in PowerBi services

And more 😅



Business related terms-
Gross price,
Pre-invoice deductions,
Post-Invoice deductions,
Net Invoice sale,
Gross Margin,
Net sales,
Net profit,
COGC - cost of goods sold,
YTD - Year to Date,
YTG - Year to Go,
Direct,
Retailer,
Distributors,
Consumer

Company’s back ground:
AltiQ hardware is a company which has grown vastly in the recent years, and opened business all over the globe. It is a company which sells, computer and computer accessories through three mediums/channel


Dataset Understanding.

Understanding what data is available will be more helpful while doing analysis. before jumping on to the analysis get good understanding of what are data available.

Dimension table : It will have the static data like details of customer and products

Fact table : It will have the data about the transactions

gdb041:

dim_customer
27 distinct markets (ex India, USA, spain)

75 distinct customers thorough out the market

2 types of platforms

Brick & Motors - Physical/offline store

E-commerce - Online Store (Amazon, flipkart)

Three channels
Retailer
Direct
Distributors

dim_market

27 distinct markets (ex India, USA, spain)

7 sub-zones

4 regions

APAC

EU

NA

LATAM

dim_product

Divisions

P & A

Peripherals

Accessories
etc, 
There are 14 different categories, Like Internal HDD, keyboard
There are different variants available for the same product

fact_forecast_monthly -
This table is used to forecast the customer’s need in advance, which can help in
Higher customer satisfaction
Reduced cost in warehouses for storage purpose
The table is denormalized by data engineering team, as it is a data warehouse which is aimed to be used for analytical work.
All the date of the month will be replaced by the start date of the month
It will have all the column names and in the end it will have the forecast quantity need of the customer
fact_sales_monthly
This table is more or less is same as fact_forecase_monthly table, but the last column has the value of sold quantity instead of forecast value.
gdb056
freight_cost
This table has details of travel cost and other cost for each market with fiscal year
gross_price
Has the details of gross prices with product code
manufacturing_cost
Has the details of manufacturing cost with product code with year
Pre_invoice_dedutions
Has the details of pre invoice deductions percentage for each cutomer with year
Post_invoice_deductions
Post invoice deductions and other deductions details
Importing data into PowerBi
As the database is MySQL in this project, we need to import the datasets from Mysql database to PowerBi by providing the Database access credential
Data Model
Data modeling plays a vital role and is considered as the basement of report. All the visuals will be build upon the data model.
Poor data modeling affects the over all performance of the report.
Following Good practices of data modeling is must. Refer this page to get to know the good practices Blog
In this project, we have followed Snowfall data modeling method.


Dashboard designing
Based on the mock ups received as requirement, the team will start designing the visuals and create measure as and when required

Home view
In Home view, all the views button will be available. User will land on specific view page by clicking the button

Info
Finance View
Sales View
Marketing View
Supply chain View
Executive View
Products
Support
Overall Report
Overall Report.gif


Project Outcome:

By using this report, decisions can be taken based on the data. Further it will help in answering n number of why questions based on the situations.
