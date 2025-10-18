This project is an attempt to simulate real-time insurance customer and claim data, move it from a NoSQL database (MongoDB) to a cloud warehouse (Snowflake) using Airbyte, transform the data with DBT.
The resultant data can be used for business reporting and/or analytics as needed.

Stack:
MongoDB → NoSQL OLTP database
Airbyte → ETL/ELT connector (Ingest data to warehouse)
Snowflake → Cloud Data Warehouse
DBT → SQL-based data transformations
Python → Data simulation and helpers

