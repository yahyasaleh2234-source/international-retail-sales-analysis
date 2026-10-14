# International Retail Sales Analysis

## Project overview
An Excel analysis of international retail transactions, with summaries of revenue by country, calendar month, product description, and price band.

## Tools
- Microsoft Excel
- PivotTables, formulas, and charts

## Key findings
- The Engineered sheet contains 83,413 records.
- Net revenue is £2,829,778.68.
- EIRE has the highest net revenue by country.
- October has the highest revenue in the combined calendar-month view.
- POSTAGE and Manual are the top two invoice descriptions by completed revenue.

## Limitation
The workbook does not fully reconcile the Clean-to-Engineered record-count difference. The gap is documented as an unresolved limitation.

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
| Countries in the report | 42 |

## Data Reconciliation and Limitations

The initial international dataset contained 84,756 transaction lines.

During data cleaning, Excel reported the removal of 1,326 duplicate records.

Expected remaining records:

84,756 - 1,326 = 83,430

However, the final Engineered worksheet contains 83,413 records.

**Unresolved discrepancy: 17 records.**

This difference has been documented as a data quality limitation. Further investigation is required to identify the reason for the missing records and establish a complete reconciliation.

The reported financial results are based on the final Engineered dataset.

