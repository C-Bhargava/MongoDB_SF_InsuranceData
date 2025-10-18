This project is an attempt to simulate real-time insurance customer and claim data, move it from a NoSQL database (MongoDB) to a cloud warehouse (Snowflake) using Airbyte, transform the data with DBT.
The resultant data can be used for business reporting and/or analytics as needed.

Stack:
1. MongoDB → NoSQL OLTP database
2. Airbyte → ETL/ELT connector (Ingest data to warehouse)
3. Snowflake → Cloud Data Warehouse
4. DBT → SQL-based data transformations
5. Python → Data simulation and helpers


