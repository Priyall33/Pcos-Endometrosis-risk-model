# PCOS & Endometriosis Risk Prediction Model

## Status
🚧 In Progress — Expected completion April 22, 2026

## Problem
PCOS and endometriosis affect 1 in 10 women but take 7–10 years 
to diagnose on average, costing the US economy ~$80B annually.

## Solution
A two-model ML system trained on CDC public health data that 
predicts risk before symptoms become severe enough for diagnosis.
Designed as a real-time risk scoring feature for women's health apps.

## Planned Models
- **Model 1 — Hormone Risk Model:** XGBoost trained on CDC NHANES
- **Model 2 — Lifestyle Risk Model:** XGBoost trained on CDC BRFSS

## Tech Stack
Python, XGBoost, SHAP, SMOTE, pandas, scikit-learn

## Data Sources
All data publicly available from CDC — not included in this repo:
- CDC NHANES: https://wwwn.cdc.gov/nchs/nhanes
- CDC BRFSS: https://www.cdc.gov/brfss/annual_data/annual_2023.html
- CDC NHIS: https://www.cdc.gov/nchs/nhis

## Results
To be updated after modeling is complete
