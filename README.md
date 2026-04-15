# Cafe Sales Data Analysis

## Project Overview
This project involves cleaning, analyzing, and visualizing cafe sales 
transaction data using Excel, Python, and Power BI.

## Dataset
- **Source:** Dirty Cafe Sales Dataset
- **Size:** 10,000 transactions
- **Columns:** Transaction ID, Item, Quantity, Price Per Unit, 
Total Spent, Payment Method, Location, Transaction Date

## Tools Used
- **Excel** — Initial data cleaning
- **Python (Jupyter Notebook)** — Data analysis and transformation
- **Power BI** — Data visualization and dashboarding

## Data Cleaning Steps (Excel)
- Split Transaction ID into TXN prefix and Transaction Number
- Replaced ERROR and UNKNOWN values with blanks
- Filled blank text columns with "Unknown" placeholder
- Filled blank numeric columns with column averages
- Filled blank dates with placeholder date

## Python Analysis
- Cleaned and standardized column names
- Converted Transaction Date to datetime format
- Extracted Month and Year from Transaction Date
- Calculated total revenue
- Analyzed revenue by Item, Payment Method, Location and Month
- Identified best selling items
- Exported final clean CSV for Power BI

## Key Findings
- Total Revenue across all transactions
- Most popular items by quantity sold
- Revenue split across payment methods (Credit Card, Cash, Digital Wallet)
- Revenue split across locations (In-store vs Takeaway)
- Monthly revenue trends

## Files
- `CAFE_SALES_CLEANED.csv` — Excel cleaned data
- `CAFE_SALES_FINAL.csv` — Python processed data (Power BI ready)
- `cafe_sales_analysis.ipynb` — Jupyter Notebook with full analysis

## Power BI Dashboard
Coming soon — visuals include:
- Revenue by Item
- Revenue by Month
- Revenue by Payment Method
- Revenue by Location
- Best Selling Items
