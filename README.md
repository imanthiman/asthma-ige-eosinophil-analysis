# Asthma IgE and Eosinophil Analysis

## Project Overview

This project analyzes the role of total immunoglobulin E (IgE) levels and blood eosinophil counts in predicting hospitalization risk among pediatric asthma patients. The data derives from a retrospective clinical study of 60 children diagnosed by pediatric specialists, divided evenly between outpatient and hospitalized groups (including ward and PICU admissions). Total IgE levels above 100 IU/ml and eosinophil counts above 450/microliter were considered positive indicators.

## Motivation

Childhood asthma is a complex, prevalent respiratory disease worldwide. Exacerbations often lead to complications, increased healthcare costs, and sometimes mortality. Previous research has suggested IgE and eosinophils as predictive biomarkers for asthma exacerbations, but studies specifically focused on pediatric populations are limited. This project seeks to fill that gap by investigating these biomarkers' association with hospitalization, including the influence of sex on outcomes.

## Data

- Data derived from a medical thesis during clinical internship.
- Dataset contains counts of patients stratified by IgE levels (>100 vs ≤100), eosinophil counts (>450 vs ≤450), sex, and admission status (outpatient, ward, ICU).
- Due to absence of raw patient-level data, analyses use reconstructed contingency tables.

## Methods

- Constructed 2×2 and 2×3 contingency tables based on summary counts.
- Performed chi-square and Fisher’s exact tests for association.
- Calculated odds ratios where appropriate.
- Visualized admission rates by IgE and eosinophil groups using bar plots.
- Analysis implemented in Python using pandas, scipy, statsmodels, matplotlib, and seaborn.

## Results

- Found statistically significant associations between IgE levels and admission status.
- Eosinophil counts showed trends toward association with admission.
- Results support clinical relevance of IgE as a biomarker in pediatric asthma severity.

## Limitations

- Data reconstructed from summary tables; no access to patient-level data.
- Small sample size (n=60) limits statistical power.
- Hospitalized patients included both ward and PICU cases with varying severity.
- Blood biomarker cutoffs based on clinical literature.
- Potential confounders (e.g., comorbidities) not accounted for.
- Findings should be interpreted with caution and validated in larger cohorts.

## Technologies Used

- Python (3.11)
- pandas
- scipy
- statsmodels
- matplotlib
- seaborn
- Jupyter Notebook

## How to Use

1. Clone the repository.
2. Open the notebook `notebooks/asthma_analysis.ipynb`.
3. Follow step-by-step analysis cells.
4. Modify or extend analyses as needed.

## Author

Iman Taheri, MD  
Aspiring Clinical Data Analyst  
[GitHub](https://github.com/imanthiman) | [LinkedIn](https://linkedin.com/in/imanthiman)