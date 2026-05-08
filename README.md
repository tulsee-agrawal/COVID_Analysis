# COVID-19 Analytics Pipeline using PySpark

## Project Overview

This project is an end-to-end COVID-19 analytics pipeline built using PySpark.  
The project processes multiple real-world COVID datasets and performs:

- Data loading
- Data cleaning
- Aggregations
- Time-series analysis
- Window function analysis
- Join operations
- Geographic analysis
- Feature engineering
- Data export and visualization

The main goal of this project is to generate meaningful insights from COVID-19 data using scalable data engineering techniques.

---

## Tech Stack

- PySpark
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## Datasets Used

- full_grouped.csv
- covid_19_clean_complete.csv
- country_wise_latest.csv
- day_wise.csv
- usa_county_wise.csv
- worldometer_data.csv

Dataset Source:  
https://www.kaggle.com/datasets/imdevskp/corona-virus-report

---

## Features Implemented

### Module 1 — Data Loading
- Loaded multiple CSV datasets using PySpark
- Schema inference
- Row count analysis

### Module 2 — Data Cleaning
- Handled missing values
- Standardized country names
- Duplicate validation

### Module 3 — Aggregations
- Top countries by confirmed cases
- Death rate analysis
- WHO region summaries

### Module 4 — Time-Series Analysis
- Daily new case trends
- Death growth percentage
- Monthly case growth

### Module 5 — Window Functions
- Top countries per WHO region
- Daily case increase analysis

### Module 6 — Join Operations
- Multi-dataset joins
- Dataset mismatch analysis
- Infection rate calculations

### Module 7 — Geographic Analysis
- USA state-wise distribution
- Latitude-longitude case clusters

### Module 8 — Advanced Analytics
- Recovery rate analysis
- Active case burden analysis
- Pandemic peak detection

### Module 9 — Feature Engineering
- Severity category generation

### Module 10 — Final Pipeline
- Generated analytics reports
- Exported processed datasets
- Created visualization-ready outputs

---
