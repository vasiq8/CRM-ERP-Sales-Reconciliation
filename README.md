# CRM-ERP Sales Reconciliation

_Validating sales transactions across CRM and ERP systems, detecting anomalies, and ensuring rebate and incentive accuracy using Excel and Power BI._

---

## Table of Contents
- [Overview](#overview)
- [Business Problem](#business-problem)
- [Objectives](#objectives)
- [Dataset](#dataset)
- [Tools & Technologies](#tools--technologies)
- [Project Structure](#project-structure)
- [Methodology](#methodology)
- [Validation Rules](#validation-rules)
- [Key Metrics & KPIs](#key-metrics--kpis)
- [Deliverables](#deliverables)
- [How to Use This Project](#how-to-use-this-project)
- [Key Findings](#key-findings)
- [Author & Contact](#author--contact)

---

## Overview

This project reconciles sales transactions between CRM and ERP systems to identify discrepancies, pricing violations, rebate errors, and incentive miscalculations. The analysis ensures data integrity, compliance, and accurate financial reporting[file:2].

---

## Business Problem

Organizations face significant challenges when CRM and ERP systems produce conflicting sales data, leading to:
- Pricing violations and discount breaches
- Incorrect rebate allocations
- Duplicate or fraudulent transactions
- Miscalculated sales agent incentives

These issues impact profitability, compliance, and stakeholder trust in financial reporting[file:2].

---

## Objectives

- **Data Validation**: Standardize dates and IDs, remove duplicates, ensure mandatory fields are populated
- **Anomaly Detection**: Compare CRM vs ERP transactions to flag mismatches, discount breaches, and rebate errors
- **Rebate & Incentive Accuracy**: Apply category-based rebates (A=5%, B=10%, C=0%) and calculate incentives at 2% of net sales
- **Reporting & Visualization**: Build KPI dashboards, exception reports, and trend analysis by month, product, and agent[file:2]

---

## Dataset

The project uses the following datasets:

| File | Description |
|------|-------------|
| `erp_transactions.csv` | Posted transactions from ERP (system of record) |
| `crm_transactions.csv` | CRM transactions after cleaning and deduplication |
| `products.csv` | Product master data |
| `customers.csv` | Customer master data |
| `price_list.csv` | Standard pricing reference |
| `rebate_policy.csv` | Category-based rebate rules |
| `incentive_policy.csv` | Sales agent incentive rules |
| `sales_agents.csv` | Sales agent information |
| `calendar_month.csv` | Calendar dimension for time analysis |
| `policies_and_rules.txt` | Validation rules documentation |

[file:2]

---

## Tools & Technologies

- **Microsoft Excel** (Power Query, DAX, Pivot Tables)
- **Power BI** (Interactive dashboards and visualizations)
- **GitHub** (Version control and project documentation)

[file:2]

---

## Project Structure

