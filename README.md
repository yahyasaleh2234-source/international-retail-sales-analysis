# International Retail Sales Analysis

## Project overview
An Excel analysis of international retail transactions, with summaries of revenue by country, calendar month, product description, and price band.

## Tools
- Microsoft Excel
- PivotTables, formulas, and charts

## Key findings

- The Engineered dataset contains 83,413 transaction records.
- Net revenue is £2,829,778.68.
- EIRE has the highest net revenue by country.
- Nigeria has the lowest net revenue.
- October has the highest revenue in the combined calendar-month view.
- April has the lowest revenue in the same view.
- The calendar-month analysis combines all available years.
- POSTAGE and Manual rank first and second by completed revenue among invoice descriptions.
- These descriptions are not necessarily physical products.
- Financial summaries were checked against the Engineered dataset.

## Limitation

The final analysis uses 83,413 records. The three-field duplicate-removal rule excluded 17 additional records beyond the 1,326 fully identical duplicates. These 17 records require business-level review before they can be classified as genuine duplicates.

The financial results represent the existing Engineered dataset, not a revised transaction population.

## Files
- Excel workbook
- Project summary in PDF and Word formats
- Chart screenshots

## Project Performance Metrics

The following table summarizes the key results of the International Retail Sales Analysis.

| Metric | Project Result |
|---|---:|
| Original Excel data rows | 1,048,575 |
| UK transaction lines excluded | 963,819 |
| International lines identified | 84,756 |
| Duplicates reported removed | 1,326 |
| Final analyzed records | 83,413 |
| Completed revenue | £3,018,790.91 |
| Cancelled revenue | -£189,012.23 |
| Net revenue | £2,829,778.68 |
| Completed transaction lines | 80,656 |
| Cancelled transaction lines | 2,757 |
| Missing Customer IDs | 2,944 |
| Country/region labels in the report | 42 |

## Data Reconciliation and Limitations

The international dataset contained 84,756 transaction records.

### Duplicate analysis

| Reconciliation metric | Records |
|---|---:|
| International transaction records | 84,756 |
| Fully identical duplicate rows | 1,326 |
| Additional rows excluded by the three-field duplicate key | 17 |
| Total excluded records | 1,343 |
| Final Engineered records | 83,413 |

### Methodological finding

The duplicate-removal method used Invoice, StockCode, and Quantity as its comparison key.

A subsequent review found that some rows sharing this key had differences in other transaction fields, including prices.

Therefore, the 17 additional excluded records cannot automatically be classified as fully identical duplicates.

The record-count difference is mathematically explained by the duplicate-key method, but whether every excluded transaction should have been removed remains a business-rule limitation.

### Reporting scope

All published financial KPIs, country comparisons, calendar-month analysis, price-band summaries, and Top 10 rankings refer to the existing Engineered dataset.

The Excel workbook and its original reported financial results remain unchanged.

