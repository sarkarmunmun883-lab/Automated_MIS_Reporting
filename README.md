# Automated MIS Reporting System

An Excel-based Management Information System (MIS) portfolio project that organizes operational records into monthly performance summaries, exception reporting, and a management dashboard.

> **Dataset note:** The workbook describes its 3,000 records as realistic sample data covering April–September 2026. Treat it as a demonstration dataset, not verified company data.

## Project Highlights

- **3,000 operational records** in the `Raw_Data` worksheet
- Employee reference information in `Master_Data`
- Monthly, department-level summaries in `MIS_Monthly`
- Follow-up flags for records that are not completed in `Exception_Report`
- KPI summary and two charts in `Dashboard`
- Excel formulas including `SUMIFS`, `COUNTIFS`, `IFERROR`, `AVERAGEIFS`, and date-based monthly logic
- Excel Tables and conditional formatting

## Workbook Structure

| Worksheet | Purpose |
|---|---|
| `README` | Workbook overview and workflow |
| `Raw_Data` | Operational source records |
| `Master_Data` | Employee, department, and location reference data |
| `MIS_Monthly` | Monthly metrics grouped by department |
| `Exception_Report` | Pending and at-risk records with suggested follow-up actions |
| `Dashboard` | Management KPIs and monthly target-versus-achievement charts |

## Workflow

`Raw_Data` → `Master_Data` → `MIS_Monthly` → `Exception_Report` → `Dashboard`

## Key Metrics

- Total records
- Total target and achievement
- Achievement percentage
- Average quality score
- Completed, at-risk, and pending counts
- Customer tickets
- Monthly target versus achievement

## How to Use

1. Download `Automated_MIS_Reporting.xlsx`.
2. Open it in Microsoft Excel with formula calculation enabled.
3. Review `Raw_Data` and `Master_Data` first.
4. Explore `MIS_Monthly` and `Exception_Report`.
5. Open `Dashboard` for the management summary.

For best compatibility, use a recent desktop version of Microsoft Excel. Formula results and chart rendering may vary in other spreadsheet applications.

## Tools & Skills Demonstrated

- Microsoft Excel
- Management reporting (MIS)
- Data organization and reference data
- Conditional aggregation and date logic
- KPI reporting and dashboard design
- Exception monitoring and follow-up prioritization

## Future Enhancements

- Add validated data-entry forms and stronger input checks
- Add slicers or interactive filters for month, department, and location
- Automate scheduled PDF/email distribution with an approved workflow
- Add a documented refresh and quality-check process
- Capture dashboard screenshots in the `screenshots/` folder

## Limitations

This is a portfolio demonstration, not a production MIS. Validate formulas and business rules against real requirements before operational use. Scheduled email/PDF distribution is a proposed extension and is not claimed to be implemented in this workbook.
