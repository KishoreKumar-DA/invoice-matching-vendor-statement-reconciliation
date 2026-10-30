# Invoice Matching & Vendor Statement Reconciliation | Advanced Excel

## Project Overview

This project focuses on supplier invoice matching, purchase order validation, vendor statement reconciliation, and payment discrepancy analysis using Microsoft Excel.

The objective is to simulate Accounts Payable (AP) operations by comparing supplier invoices against purchase orders, reconciling vendor statements, identifying discrepancies, and monitoring outstanding payment balances.

The project uses synthetic financial data to demonstrate practical Excel-based reconciliation and exception management techniques.

## Business Objectives

- Match supplier invoices against purchase orders to validate invoice details and amounts.
- Reconcile vendor statements against internal invoice records.
- Identify duplicate invoices, missing records, and amount discrepancies.
- Analyse payment records to identify partial, failed, and pending payments.
- Monitor outstanding balances and support accurate vendor account reconciliation.

## Tools & Technologies

- Microsoft Excel
- XLOOKUP
- SUMIFS and COUNTIFS
- IF and IFERROR
- Conditional Formatting
- PivotTables and PivotCharts
- Data Validation
- Excel Dashboard Reporting

## Dataset Overview

The project uses a synthetic dataset containing the following records:

| Dataset | Records |
|---|---:|
| Purchase Orders | 180 |
| Supplier Invoices | 210 |
| Vendor Statements | 240 |
| Payment Records | 170 |
| Vendor Master | 12 |

The dataset includes deliberately introduced exceptions such as duplicate invoice references, quantity and price variances, unmatched statement entries, credit notes, partial payments, failed payments, and pending payments.

## Project Workflow

### 1. Purchase Order Matching
- Match supplier invoices against purchase orders.
- Validate vendor IDs, PO references, item codes, quantities, and unit prices.
- Identify missing or invalid purchase order references.

### 2. Invoice Validation
- Compare billed quantities and unit prices against approved purchase orders.
- Calculate invoice amount differences.
- Identify duplicate invoice references and potential overbilling.

### 3. Vendor Statement Reconciliation
- Compare vendor statement references against internal supplier invoice records.
- Identify missing invoices and unmatched statement entries.
- Investigate differences between vendor statement amounts and recorded invoice amounts.

### 4. Payment Reconciliation
- Analyse payment records against supplier invoices.
- Identify successful, failed, pending, and partial payments.
- Calculate outstanding invoice balances.

### 5. Exception Analysis
- Classify reconciliation exceptions.
- Identify records requiring further investigation.
- Prepare exception summaries to support vendor account follow-up.

## Key Business Questions

1. Which supplier invoices do not have a matching purchase order?
2. Are there duplicate supplier invoice references?
3. Which invoices contain quantity or unit price discrepancies?
4. Which vendor statement entries are missing from internal records?
5. Which vendors have outstanding invoice balances?
6. Which payments are failed, pending, or partially completed?
7. What are the major causes of invoice reconciliation exceptions?

## Expected Business Value

- Improves visibility into invoice matching and reconciliation exceptions.
- Helps identify potential duplicate invoices and payment discrepancies.
- Supports vendor statement reconciliation and outstanding balance monitoring.
- Provides structured exception reports for investigation and follow-up.
- Demonstrates practical Excel skills relevant to Accounts Payable and Finance Operations.

## Project Files

- `Invoice_Matching_Vendor_Statement_Reconciliation_Synthetic_Data.xlsx`
- `README.md` – Project documentation.

## Skills Demonstrated

Advanced Excel | Invoice Matching | Purchase Order Validation | Accounts Payable | Vendor Statement Reconciliation | Payment Reconciliation | Exception Analysis | Data Validation | Financial Reporting
