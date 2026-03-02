# Excel Formula 1 Data Analysis Dashboard

## Overview
This project consolidates and analyzes historical Formula 1 race data to build a fully interactive and professional Excel dashboard. The workflow covers data cleaning, transformation, feature engineering, and advanced pivot-based reporting.

## Dataset

The analysis uses the **Formula 1 World Championship (1950–2020)** dataset from Kaggle.

Dataset link:  
https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020


---

## Project Workflow

### 1. Data Consolidation
- Imported multiple F1 CSV files into a single Excel workbook.
- Maintained one sheet per dataset for structured processing.

### 2. Data Cleaning & Transformation (Power Query)
- Corrected data types
- Handled missing values
- Standardized column names
- Removed unnecessary fields
- Ensured relational consistency across tables

### 3. Data Modeling
- Merged all tables into a single master dataset using ID keys.
- Loaded into a structured Excel Table for analysis.

### 4. Feature Engineering
Created analytical features including:
- Win flag
- Podium flag
- DNF flag
- Positions gained/lost
- Driver age at race
- Lap time converted to seconds

Helper columns were added to convert Yes/No flags into numeric values for pivot compatibility.

---

## Analytical Reports

Built 5 dedicated Pivot Chart sheets:

1. Driver Points Analysis  
2. Season Points Trend  
3. Circuit Performance  
4. DNF Analysis  
5. All-Time Driver Experience  

Advanced chart types used:
- Combo charts  
- Doughnut charts  
- Dual-axis line charts  

---

## Interactive Dashboard

Designed a professional dashboard featuring:

- Title banner
- 6 KPI cards powered by:
  - `COUNTIF`
  - `AVERAGE`
  - `XLOOKUP`

### KPIs Displayed
- Total Races
- Wins
- Podiums
- DNF Rate
- Average Points
- Average Age

### Interactivity
- Embedded pivot charts
- Season slicer
- Driver Name slicer

---

## Tools Used
- Microsoft Excel
- Power Query (ETL)
- Pivot Tables & Pivot Charts
- Excel formulas for KPI calculations
- Dashboard design best practices

---

## Outcome

A fully analysis-ready Excel dashboard that provides deep insights into:
- Driver performance trends
- Season-level progression
- Circuit-level insights
- Reliability and DNF patterns

This project demonstrates end-to-end Excel analytics capabilities including data transformation, modeling, visualization, and dashboard interactivity.
