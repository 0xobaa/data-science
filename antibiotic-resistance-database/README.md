# Antibiotic Resistance Database — SQL + Python

End-to-end database design and AMR surveillance analysis on a real-world antibiotic resistance dataset of 2,199 patient records.

**File:** `Antibiotic_Resistance,_SQL_+_Python_Analysis.ipynb`

## Database structure

- `Patients` — demographics and clinical outcomes
- `lab_results` — antibiotic susceptibility per patient
- `Resistance_summary` — aggregated resistance-gene prevalence

## Key findings

- Meropenem carried the highest resistance rate at 34.29%, which is alarming for a third-line antibiotic
- The VIM resistance gene was most associated with deceased patients (167 cases)
- Disc diffusion detected the most resistant cases across all antibiotics (1,225)
- Female patients had a marginally higher mortality rate (32.07% vs 30.30%)
- Blood, stool, and urine specimens showed the highest Meropenem resistance, around 36%

## Recommendations

Review carbapenem prescribing protocols urgently, tighten VIM surveillance in high-mortality cohorts, and take a closer look at how bloodstream infections are being managed.

## Stack

Python, pandas, SQLAlchemy, SQLite, Matplotlib, Seaborn. Skills: database design, SQL query writing, pandas-to-SQL integration, `CASE WHEN` logic, percentage calculations, visualisation.
