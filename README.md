# Bank-Audit-compliance-Report
Project Overview
This project automates the process of reconciling financial records and generating compliance reports by comparing data from a bank statement and an internal ledger. The goal is to identify mismatches, flag non-compliance, and present the results visually for easier interpretation.

## Key features of the project include:
Data Reconciliation: Match transactions between the bank statement and internal ledger.
Compliance Checks: Verify if transactions adhere to specified rules.
Interactive Visualizations: Present reconciliation and compliance results in Power BI.

## Libraries Used
Pandas: For data manipulation and analysis.
NumPy: For numerical operations.
## Technologies Used
Python: For data processing and analysis.
Power BI: For creating interactive dashboards and visualizations.
CSV: For input and output data storage.
Jupyter Notebook: For coding and running analysis steps interactively.

## Features
### Data Processing:
Uses Python for loading, processing, and validating transaction data.
Identifies unmatched or missing records for reconciliation.
Compliance Reporting:
Flags transactions as compliant or non-compliant based on matching criteria.
### Visualization:
Power BI dashboard visualizes: 
Compliance status (true/false) in a pie chart.
Transaction details (ID, account, amount, and date) in a table format.

## Project Structure
/BankAudit-Reconciliation
├── README.md                     # Project overview and instructions
├── data/                         # Sample datasets
│   ├── bank_statement_sample.csv # Example bank statement
│   ├── internal_ledger_sample.csv # Example internal ledger
├── notebooks/                    # Jupyter Notebook for the project
│   ├── audit_reconciliation_with_compliance_checks.ipynb
├── visuals/                      # Power BI visualizations
│   ├── power_bi_dashboard.png    # Screenshot of dashboard
├── scripts/                      # Python scripts (optional)

## How It Works
### Input Data:
 Bank Statement: Contains transaction dates, descriptions, amounts, and account numbers.
 Internal Ledger: Contains transaction dates, IDs, amounts, vendors, and account numbers.
### Processing Logic:
 Data is loaded and processed in Python using Pandas.
 Reconciliation is performed by matching transaction details between the two datasets.
 Compliance status is assigned based on transaction matches.
### Output:
 Reconciliation Report: Highlights matched and unmatched transactions.
 Compliance Report: Flags transactions as compliant or non-compliant.
 Data is exported for visualization in Power BI.

## Visualization
The Power BI dashboard includes:
Pie Chart: Visualizes the percentage of compliant and non-compliant transactions.
Transaction Table: Displays transaction details, including ID, account, amount, and date.


## Sample Datasets
input files
1) bank_statement_sample.csv: Simulated bank statement data.
2) internal_ledger_sample.csv: Simulated internal ledger data.

## Contact
If you have questions or feedback, feel free to contact me via GitHub.

