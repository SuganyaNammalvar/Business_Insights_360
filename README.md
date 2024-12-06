# Business_Insights_360

**Project Objective:**

Atliq hardware company is growing rapidly in recent years however due to unforeseen circumstances, the company is experiencing enormous losses.So AtliQ company buliding their data analytics team utilising Power Bi to develop a dashboard in order to make data-driven decisions. 


**Tools used:**

- MySQL database

- Power Bi

- Excel

- Power Query

- DAX Language


**Business Terminologies:**
 
- Gross Price

 - Pre-invoice deductions

 - Net Invoice sales

 - Post-invoice deductions

-  Net sales

 - Cost of Goods Sold(COGS)
 
 - Gross Margin

 - Net Profit

 - Benchmark

 - YTD(Year-to-date)

 - YTG(Year-to-go)

 **Dataset Explanation:**

Dataset is used for analysis,reporting and decision-making.In Power Bi,datasets are the foundation for creating visualizations and performing analytics.

**Dimension Table:It contains attributes on that truth table calculates the metric.While in dimension table,there is  more attributes than fact table

*Fact Table:It contains the measuring of the attributes of a dimension table.
 
- gdb041:

   dim_customer,
   dim_market,
   dim_product,
   fact_forecast_monthly,
   fact_sales_monthly

- gdb056:

   freight_cost,
   gross_price,
   manufacturing_cost,
   pre_invoce deductions,
   post_invoice_deductions

  **Importing Data into Power BI **
   
   Since my data is in MYSQL ,we have to import from MYSQL to Power BI by providing valid database credential.

**Power Query:**

 After importing dataset ,transform data in power query.It is a tool for ETL(Extract-Transform-Load).It is the place where ypu can change the datatype  of the column operation,format 
 operation,merge,replace,pivot,unpivot and so on..

**Data Modelling:**
  
   Data modelling is a very important part of the data anlaytics pipeline .It allows you to visually set the relationship between the tables.In this project,we have followed snowflake data modelling method.
   
![image](https://github.com/user-attachments/assets/62f5e0fb-440c-46ba-a48f-2f47cbdce9e1)

   
**Dashboard Overview:**

Users can view the visuals by clicking the button.

- Info

- Finance view

- Sales View 

- Supply Chain View
 
- Marketing view

- Executive view

- Support


   ![image](https://github.com/user-attachments/assets/8f17f9e6-8f44-446d-95d7-dafd2624914b)

 **Home Info:**

  ![image](https://github.com/user-attachments/assets/c9ffb63d-94c6-4864-8f58-23654d415684)

  **Finance view:**

  ![image](https://github.com/user-attachments/assets/2ee85f6a-7725-484b-ac4c-065ba39a0e38)

  **Sales View:**
  
![image](https://github.com/user-attachments/assets/20067888-4712-4d2e-9068-83201e17dc0a)

**Marketing View:**

![image](https://github.com/user-attachments/assets/95f68ab3-a522-41d0-b234-3ae394d5e063)

**Supply Chain View:**

![image](https://github.com/user-attachments/assets/ee31f708-9840-4031-beed-321bc8c6cdb9)

**Executive View:**

![image](https://github.com/user-attachments/assets/87082b24-435b-44d8-9a17-dfe84560f802)








