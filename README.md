# Superstore Excel Data Analysis

An end-to-end **Microsoft Excel sales analysis project** using the Sample Superstore dataset. The project focuses on preparing data with Power Query, analyzing performance with PivotTables, and presenting findings through charts.

## Project overview

The workbook contains the source data, a cleaned analysis table, PivotTable-based analysis, and charts.

### Analysis included

- Sales and profit by region
- Sales by customer segment
- Sales by shipping mode
- Monthly sales trends
- Sales by state
- Top 10 products by sales
- Profit by product sub-category

## Key figures

| Metric | Result |
|---|---:|
| Records | 9,994 |
| Columns | 21 |
| Unique orders | 5,009 |
| Units sold | 37,873 |
| Total sales | $2,297,200.86 |
| Total profit | $286,397.02 |

## Tools and skills

- **Microsoft Excel** — analysis and reporting
- **Power Query** — data preparation and transformation
- **PivotTables** — aggregations and comparisons
- **PivotCharts** — visual presentation
- **Data validation** — checking row counts, unique IDs, blanks, and date consistency

## Visual previews

### Sales by region
![Sales by Region](Screenshots/Sales_by_Region.png)

### Sales by customer segment
![Sales by Segment](Screenshots/Sales_by_Segment.png)

### Profit by sub-category
![Profit by Sub-Category](Screenshots/Profit_by_SubCategory.png)

### Top 10 products by sales
![Top 10 Products by Sales](Screenshots/Top_10_Products_by_Sales.png)

## Repository files

- [Excel workbook](Superstore_Data_Analysis.xlsx) — main project file
- [Analysis summary](Analysis_Summary.csv) — key metrics
- [Data quality checks](Data_Quality_Checks.csv) — validation results
- [Screenshots](Screenshots/) — chart previews

## Data quality note

The validation found **1,708 records where Ship Date is earlier than Order Date**. These values were not changed because the correct dates could not be confirmed from the available source. Treat date-based findings with this limitation in mind.

## Author

**Sandeep Singh**

This project was completed as part of my practical learning in Excel and data analysis.
