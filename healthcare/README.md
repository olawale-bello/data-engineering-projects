# Healthcare Readmission Pipeline

## Overview
Patient readmission prediction pipeline using Python for automated 
data cleaning, Azure for cloud storage and orchestration, and Power BI 
for clinical insights.

## Tech Stack
- Python / Pandas
- Azure Blob Storage
- Azure Data Factory (Daily Schedule Trigger)
- Azure SQL Database
- Power BI

## Key Results
- 8,000 rows processed
- 17 data columns cleaned
- 6 Power BI visuals
- Daily automated pipeline trigger

## Pipeline
Raw CSV → Python Cleaning → Blob Storage → ADF → Azure SQL → Power BI

## Data Issues Fixed
- 50 duplicate rows removed
- 150 NULL age values imputed
- 50 NULL gender values filled
- 101 NULL insurance values filled
- Negative age and length_of_stay corrected
- Inconsistent casing standardised
