CRM–ERP Sales Reconciliation


Problem Statement
Organizations rely on ERP and CRM systems to track customer transactions, rebates, and sales agent incentives. However, discrepancies between these systems often result in:
Pricing violations and discount breaches
Incorrect rebate allocations
Duplicate or fraudulent transactions
Miscalculated sales incentives
These issues affect profitability, compliance, and trust in financial reporting.
This project focuses on validating sales transactions across CRM and ERP systems, detecting anomalies, and ensuring rebate and incentive accuracy.


Objectives

Data validation and cleaning: standardize dates and IDs, remove duplicates, and ensure required fields are present.
Anomaly detection: compare CRM and ERP rows to flag mismatches, discount breaches, and incorrect rebate assignments.
Rebate and incentive checks: apply category rebates (A=5%, B=10%, C=0%) and compute incentives at 2% of net sales.
Reporting and visuals: provide KPI dashboard, exception reports, and trend views by month, product, and agent.



Datasets

ERP_transactions.csv: posted transactions used as the system of record.
CRM_transactions.csv: CRM transactions after cleaning and de‑duplication.
products.csv, customers.csv, price_list.csv: master data and price references.
rebate_policy.csv, incentive_policy.csv: rules for rebates and incentives.
calendar_month.csv, policies_and_rules.txt: calendar keys and validation rules.


Methodology
Data Integration – Combined CRM, ERP, and master datasets in Excel/Power BI.
Data Cleaning – Standardized CRM data, removed duplicates, validated IDs.
Validation Rules Applied
Unique Transaction IDs.
Mandatory Customer_ID and Product_ID.
ERP prices must equal Price List.
CRM transactions flagged if Unit Price < 75% of Price List.
Rebates applied by category (A – 5%, B – 10%, C – 0%).
Incentives = 2% of net sales.
Exception Reporting – Identified missing ERP matches, rebate errors, blank IDs, and discount breaches.
Analytics & Dashboards – Built KPI dashboard, exception reports, trend pivots, and a Power BI visualization file (SalesDifference.pbix).


Deliverables
Cleaned CRM Dataset with anomalies flagged.
Rebate & Incentive Calculations at transaction and agent levels.
Exception Reports for anomalies, mismatches, and compliance breaches.
Excel Worksheets with pivots, KPIs, and trends.
Power BI Dashboard (SalesDifference.pbix) for visualization.


Summary
This project reconciles CRM and ERP sales, detects pricing and rebate issues, and highlights high‑risk agents and products through clear KPIs and simple visuals that stakeholders can act on quickly. 





