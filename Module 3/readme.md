ASSIGNMENT OVERVIEW

Data Warehousing:

For the first segment of the assignment, you will undertake a series of tasks. Initially, set up an instance of IBM DB2 on the cloud as directed in the provided link. If you have previously established an instance, you may continue using it. The initial exercise entails devising a data warehouse for an e-commerce enterprise. Utilizing sample data, craft a Star Schema, identifying columns for dimension and fact tables. Name the database 'softcart' and utilize an ERD design tool to structure the 'softcartDimDate' table, incorporating fields like DateID, Month, Monthname, etc. The company aims to generate reports based on yearly, monthly, daily, and weekday criteria.

Subsequent tasks involve designing dimension tables such as 'softcartDimCategory' and 'softcartDimCountry', along with the 'softcartFactSales' fact table, utilizing the ERD design tool. Finally, establish the requisite relationships (one-to-one, one-to-many, etc.) among the tables using the ERD design tool. After each task, capture a screenshot displaying the complete ERD, including all field names, data types, and table relationships.

In the second exercise, load data into the data warehouse. Your senior Data Engineer has refined your schema design. Obtain the data based on the updated schema from the provided link and restore it into a database named 'staging' using the pgAdmin tool. After completing this task, capture a screenshot demonstrating the successful restoration of data.

Data Warehousing Reporting:

In this segment of the assignment, you will conduct a series of exercises. Initially, set up an instance of IBM DB2 on the cloud as instructed in the provided link. If you have an existing instance, proceed using it. The initial task involves loading data provided by the company, in CSV format, into tables by following specific steps. Begin by downloading the data from the provided links and then load it into tables such as DimDate, DimCategory, DimCountry, and FactSales. After loading the data, capture screenshots of the first five rows in each table and name the screenshots accordingly.

In the second exercise, query the loaded data by creating grouping sets, rollup, and cube queries using columns like Orderid, Category, and Price. Additionally, create an MQT (Materialized Query Table) named 'Total_sales_per_country' utilizing country and total sales columns. After completing each task, capture a screenshot displaying the SQL query and the resulting output rows, and name the screenshots appropriately.
