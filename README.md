I wanted to analyze healthcare claim costs across patients, providers, drugs, and time, using real-world healthcare concepts like medical claims and pharmacy claims.
I designed and implemented a mini healthcare data warehouse with staging, dimensional and fact layers following a star-schema approach.

*Architecture explained:*

- Imported raw CSV data into staging tables

- Cleaned & standardized the data

- Built dimension tables (patient, provider, drug, date)

- Built fact tables (medical claims + pharmacy claims)

- Loaded them using SQL transformations and joins

- Ran analytics queries on top of warehouse

*Technologies used:*

MySQL, Workbench, SQL

*Key contributions:*

- Built 5 staging tables

- Modeled & created 4 dimensions

- Created 2 fact tables with >1000 rows each

- Cleaned data using SQL (TRIM, COALESCE, CASE, date conversions)

- Implemented surrogate keys

- Linked facts to dims using foreign keys

- Executed analytical queries to derive insights




