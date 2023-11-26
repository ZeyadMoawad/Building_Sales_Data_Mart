# Building_Sales_Data_Mart
# Project Description:
Building Sales Data Mart using SSIS and SQL Server Designing a data mart utilize the power of SSIS (SQL Server Integration Services) and SQL Server, using the AdventureWorks2022 database, an OLTP (Online Transaction Processing) system, as the primary data source, a widely recognized database in the realm of data analysis.

A data mart is a focused and purpose-built subset of a data warehouse, designed to cater to the specific analytical needs of a particular department, team, or business unit within an organization. Data marts are typically structured around a dimensional model, employing star schemas, which consist of dimension tables describing various attributes and a central fact table containing numerical measures.

## Key Project Tasks:
- Data Extraction from AdventureWorks2022 (OLTP)
  
- Cleanse and preprocess extracted data to ensure data quality
  
- Design the star schema for data mart.
  
- Develop ETL (Extract, Transform, Load) processes using SSIS or other ETL tools.
# Data source:
 [AdventureWorks2022 Database](https://github.com/Microsoft/sql-server-samples/releases/download/adventureworks/AdventureWorks2022.bak)
 # Steps
 Data Modeling (Star Schema)
 
![Star_schama](https://github.com/ZeyadMoawad/Building_Sales_Data_Mart/assets/96973429/8d074daf-8f88-43fa-bcf2-ea333ce68a27)
 
 Then, I used SSIS to create Fact table and the dimention packages separately for:

- Integrating the data from data source.

- Transforming and processing data.

- And then  incremental load data after applying the transformation, and apply full and slow-changing dimension (SCD) loading.
# Fact_Table
![Fact-table](https://github.com/ZeyadMoawad/Building_Sales_Data_Mart/assets/96973429/bb87c220-0dfc-43e4-831c-2dda8d2ef1b3)
# incremental Fact Table
![Fact_Table](https://github.com/ZeyadMoawad/Building_Sales_Data_Mart/assets/96973429/052d52a5-f5a4-407b-8bf7-aa8b54f408f9)
# Fact_Table Resultset
![Result_Fact_Table](https://github.com/ZeyadMoawad/Building_Sales_Data_Mart/assets/96973429/e71e9cbe-6688-49ac-b552-6720f3c17298)

# Dim_Customer
![Dim_Cutomers](https://github.com/ZeyadMoawad/Building_Sales_Data_Mart/assets/96973429/1da9eb32-c2b3-4588-96dc-f34c42d6be7c)
# Dim-Customer Resultset
![Result_Dim_Customers](https://github.com/ZeyadMoawad/Building_Sales_Data_Mart/assets/96973429/1adf89c0-e91c-482c-8459-74d0d7f0f675)
# Dim_Product
![Dim_Products](https://github.com/ZeyadMoawad/Building_Sales_Data_Mart/assets/96973429/3c81be91-4de6-4235-be24-3f02c9ca7fd9)
# Dim-Product Resultset
![Result_Dim_Products](https://github.com/ZeyadMoawad/Building_Sales_Data_Mart/assets/96973429/dba58a42-718a-4da2-b6b7-24344ef07477)
# Dim_Territory
![Dim_Temitory](https://github.com/ZeyadMoawad/Building_Sales_Data_Mart/assets/96973429/02104bf2-51e2-4f93-9d18-0f69a490468e)
# Dim_Territory Resultset
![Result-Dim_Territory](https://github.com/ZeyadMoawad/Building_Sales_Data_Mart/assets/96973429/cfc64bf5-5979-4495-bc92-9e68347b0a4d)
# Dim_Date
![Dim_Date](https://github.com/ZeyadMoawad/Building_Sales_Data_Mart/assets/96973429/7ba2088a-74fb-41b0-a0a8-dd33b088c068)
# Dim_Date Resultset
![Result_Dim_Date](https://github.com/ZeyadMoawad/Building_Sales_Data_Mart/assets/96973429/dfd40d7f-bcd2-4a1c-b97e-235d7f2103a5)










