
# SQL Data Warehouse Project

This project involves building a SQL-based data warehouse from scratch to support analytical queries on structured business data. The aim is to demonstrate data integration, transformation, and modeling techniques using a star schema approach.

## 📌 Project Description

A data warehouse is designed to store historical business data and support decision-making through efficient reporting and analysis. In this project, raw data is extracted, transformed, and loaded (ETL) into fact and dimension tables. The warehouse enables insights into key business metrics.

## 🧰 Tools & Technologies

* **SQL Server** – For data storage and querying
* **SSMS (SQL Server Management Studio)** – For development and testing
* **Star Schema** – For dimensional modeling
* **Excel** – For data inspection and preprocessing (optional)

## 🗃️ Data Model

The data warehouse follows a **star schema**, optimized for analytics. It includes:

* **Fact Table:**

  * `fact_sales` – Stores transactional sales data

* **Dimension Tables:**

  * `dim_customer` – Customer details
  * `dim_product` – Product information
  * `dim_date` – Date hierarchy (day, month, year)
  * `dim_store` – Store/region information

## 📂 Project Structure

```
├── create_tables.sql         # SQL script to create fact and dimension tables
├── insert_data.sql           # SQL script to insert and transform data
├── etl_process.sql           # End-to-end ETL workflow
└── README.md                 # Project documentation
```

## 🚀 How to Run the Project

1. Open SSMS and connect to your SQL Server instance.
2. Execute `create_tables.sql` to generate the schema.
3. Execute `insert_data.sql` to populate the tables.
4. Optionally run `etl_process.sql` if you're simulating full ETL.
5. Query the warehouse to perform analytical queries.

## 📊 Use Cases / Example Queries

* Monthly sales by product category
* Top customers by revenue
* Sales trends over time
* Regional sales performance

## ✅ Outcomes

* Learned data warehousing principles
* Built a working star schema
* Practiced SQL-based ETL
* Enabled analytical reporting from transactional data


