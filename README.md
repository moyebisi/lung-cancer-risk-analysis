# Lung Cancer Risk Factor Analysis Dashboard

A two-page Power BI dashboard exploring the relationship between six risk factors and lung cancer diagnosis, built on a 50,000-patient dataset.

![Dashboard Preview](https://raw.githubusercontent.com/moyebisi/lung-cancer-risk-analysis/main/lung_cancer_dashboard_cover.png)

## Overview

This project examines how six risk factors — asbestos exposure, COPD diagnosis, radon exposure, family history, secondhand smoke, and alcohol consumption — relate to lung cancer diagnosis rates.

## Key Findings

- **Asbestos exposure** shows the strongest association with lung cancer diagnosis (76.1% vs. 61.5%, a ~15 percentage-point gap)
- **COPD diagnosis** (~14pt) and **radon exposure** (~13pt) follow closely behind as strong risk indicators
- **Alcohol consumption** shows the weakest association (~4 percentage-point gap)
- Risk factor exposure levels are near-uniformly distributed across the population, indicating this dataset was synthetically generated rather than modeled on real epidemiological rates — a limitation transparently noted on the dashboard itself

## Tools & Skills

- **Power BI** — data modeling, report design
- **DAX** — custom SWITCH-based binning, calculated measures, percentage-of-total calculations
- **Power Query** — data cleaning (handling missing values, type correction)

## Data

50,000-row synthetic patient dataset with demographic and exposure variables. Cleaned in Power Query: missing `alcohol_consumption` values (~33% of rows) were identified as a mislabeled "None" category rather than true missing data, based on the resulting even three-way split after correction.

## Files

- `lung_cancer_dashboard_cover.png` — dashboard preview image
- Dashboard built in Power BI Desktop (.pbix file available on request / [add if uploaded])

## Author

Michael Oyebisi — [Portfolio](https://moyebisi.github.io) | [LinkedIn](https://linkedin.com/in/michael-oyebisi)
