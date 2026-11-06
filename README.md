# Superstore Sales Analysis

## About this project

I used the Sample Superstore dataset to practise cleaning data in Excel and exploring sales performance. I wanted to take a raw dataset, prepare it for analysis, and see what useful information I could get from it.

The workbook includes the original data, the cleaned table, PivotTables, and charts.

## What I worked on

- Cleaned and prepared the data in Power Query.
- Checked the columns and corrected data types where needed.
- Used Trim and Clean on text fields.
- Reviewed the data for blanks and errors.
- Built PivotTables to compare sales and profit.
- Created charts to make the results easier to understand.

## Questions explored

I used the PivotTables to look at:

- Sales and profit by region
- Sales by customer segment
- Sales by shipping mode
- Monthly sales trends
- Sales by state
- Top-selling products
- Profit by product sub-category

## Dataset at a glance

- 9,994 rows
- 21 columns
- 5,009 unique orders
- 3 product categories
- 4 regions

## Tools used

- Microsoft Excel
- Power Query
- PivotTables
- PivotCharts

## Files in this repository

- `Superstore_Data_Analysis.xlsx` — the Excel workbook with the raw data, cleaned data, analysis, and charts.
- `Analysis_Summary.csv` — a short summary of the main figures.
- `Data_Quality_Checks.csv` — the checks run on the cleaned table.
- `Screenshots/` — chart images from the analysis.

## A note about data validation

While checking the dates, I found records where the ship date appears earlier than the order date. I have left the original values unchanged rather than guessing which dates should be corrected. This needs to be checked against the source data before treating the date analysis as final.

## Author

**Sandeep Singh**

This is a practice project I completed while building my Excel and data-analysis skills.
