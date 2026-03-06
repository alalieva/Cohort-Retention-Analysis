# :bar_chart: Cohort Retention Analysis

## Overview
This project explores user retention patterns using a cohort-based approach applied to historical activity data. 
The goal is to identify early churn, measure long-term engagement stability, and surface differences between user acquisition cohorts.

## Business Questions
- How quickly do users disengage after their first activity?
- Which cohorts show the strongest long-term retention?
- At what point does retention stabilize?

## Dataset
- ~9,800 unique users, 171,000+ activity records
- Period: January 2023 – October 2024
- Source: educational dataset
  [Dataset](https://github.com/alalieva/Cohort-Retention-Analysis/blob/main/users_data.csv)

## Methodology
1. **Data quality checks** — missing values, duplicates, user-day level deduplication
2. **Cohort assignment** — each user assigned to their first activity month
3. **Retention matrix** — monthly retention rates calculated per cohort
4. **Visualizations** — heatmap and retention curves

## Key Findings
- Largest user drop occurs in the first month after initial activity, indicating activation challenges typical for digital products
- After the initial decline, retention stabilizes — long-term engaged users show consistent activity over 6+ months
- Older cohorts retain approximately 20-30% of users after 6 months

## Tools
Python · pandas · seaborn · matplotlib · Jupyter Notebook
