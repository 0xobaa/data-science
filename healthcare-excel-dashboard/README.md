# Healthcare Operations Dashboard (Excel)

An interactive Excel dashboard for exploring simulated clinical data: patient visits, malaria positivity, anemia prevalence, and hemoglobin distribution. Slicers and pivot charts let you filter and drill without touching the underlying sheet.

**File:** `healthcare-operations-dashboard.xlsx`

## Dataset

Simulated clinical records for 300 patients. Fields cover demographics, visit dates, ward admission, malaria test result, and hemoglobin level.

## Metrics

- Total patient visits
- Malaria positivity rate
- Anemia prevalence
- Average hemoglobin

## Visualisations

- Visits by ward (column chart)
- Malaria positivity by age group (stacked column)
- Monthly visit trend (line chart)
- Hemoglobin distribution (histogram)

Slicers filter the whole view by sex, ward, and malaria status.

## What the data showed

Malaria positivity ran higher among younger patients. A few wards carried noticeably heavier visit volumes than the rest. The hemoglobin spread points to moderate anemia prevalence in this cohort.

## Tools

Microsoft Excel: pivot tables, pivot charts, slicers.

## Next steps

Rebuild in Power BI for richer interactivity, move data cleaning into Python or Power Query, and wire in a SQL source so it scales past a single workbook.
