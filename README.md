# Accounting Automation Project

A Python-based tool to automate accounting for SMEs in Pakistan. It processes transaction data, calculates Income, Expenses, Profit, Capital, Assets, Liabilities, and 17% FBR-compliant Tax. Features interactive Plotly charts (bar & pie), PDF invoice generation, and a balance sheet summary.

## Features
- Auto-calculates financial metrics from CSV data.
- Generates interactive bar and pie charts with millions-based labels.
- Creates PDF invoices for Income transactions.
- Produces a balance sheet with Assets, Liabilities, and Equity.

## Screenshots
![Bar Chart](screenshots/bar_chart.png)
![Pie Chart](screenshots/pie_chart.png)

## How to Run
1. Install dependencies: `pip install pandas plotly reportlab`
2. Place `detailed_transactions.csv` in the same folder.
3. Run: `python auto_accounting_terms_with_tax_invoice_balance.py`

## Sample Output
- **Data**: `detailed_transactions.csv`
- **Invoices**: See `invoices/` folder
- **Balance Sheet**: Printed in console
