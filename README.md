I wanted to analyze healthcare claim costs across patients, providers, drugs, and time, using real-world healthcare concepts like medical claims and pharmacy claims.
I designed and implemented a mini healthcare data warehouse with staging, dimensional and fact layers following a star-schema approach.

*Architecture Explain*

- Imported raw CSV data into staging tables.

- Cleaned & standardized the data.

- Built dimension tables (patient, provider, drug, date).

- Built fact tables (medical claims + pharmacy claims).

- Loaded them using SQL transformations and joins.

- Ran analytics queries on top of warehouse.

*Technologies used:*

MySQL, Workbench, SQL.

*Key contributions:*

- Built 5 staging tables.

- Modeled & created 4 dimensions.

- Created 2 fact tables with >1000 rows each.

- Cleaned data using SQL (TRIM, COALESCE, CASE, date conversions).

- Implemented surrogate keys.

- Linked facts to dims using foreign keys.

- Executed analytical queries to derive insights.

*Findings:*

1) Monthly Trend of Total Spend
Monthly healthcare spend shows a sharp rise from Nov-2023 to Apr-2024, peaking in April, followed by a steep decline in May.

2) Top Drugs by Rx Cost
CardioPlus and RespiraMax are the highest-cost drugs, indicating major spending concentrated in cardiology and respiratory therapy.

3) Top Hospitals by Total Medical Spend
Sunrise Medical and Prime Care Clinic account for the majority of medical spending, suggesting higher utilization at these facilities.

4) Total Annual Healthcare Cost by Region
Central and East regions show the highest annual spend, indicating these geographies drive the majority of healthcare costs.

5) Top 10 Most Expensive Patients
A small group of high-utilization patients contributes disproportionately to total medical and pharmacy spend.

6) Total Medical + Pharmacy Cost per Patient
High-cost patients drive overall cost primarily through medical claims rather than pharmacy usage.






