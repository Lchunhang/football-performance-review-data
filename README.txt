# Data and scripts for  
“A Systematic Review of Modern Football Performance Measures (2018 – 2024)”

This repository contains the research data and companion materials that support the findings of the review paper:

> **Lee C. H., Mohamad A. H., Asirvatham D.**  
> *A Systematic Review of Modern Football Performance Measures (2018 – 2024).*  
> Submitted to the ACML 2025 collection, **Machine Learning** (Springer).

## Contents

| File | Description |
|------|-------------|
| **review_sheet.csv** | UTF-8 encoded spreadsheet with coded information for the 79 peer-reviewed studies included in the review. |
| **search_strings.txt** | Exact Scopus, ScienceDirect and SAGE query strings used in the PRISMA search (date range 2018–2024, English language). |

## Column guide for `review_sheet.csv`

| Column | Meaning |
|--------|---------|
| `Article Title` | Title as published. |
| `Author(s)` | First author plus “et al.” if applicable. |
| `Year` | Publication year. |
| `Purpose` | One-sentence summary of the study’s goal. |
| `Sample Size` | Number of matches, players, or seasons analysed (blank if not reported). |
| `Category` | One of **Financial**, **Individual**, **Team**, **Action**. |
| `Sample` | Data sample |
| `Geographical Representation` | Region or league focus (e.g., *Europe*, *America*). |
| `Modelling Approach` | High-level family (Regression, Ensemble, Graph, RL, etc.). |
| `Techniques/Model Used` | Specific algorithms (e.g., XGBoost, GNN-EGT). |
| `Type of Data` | **Aggregated**, **Event**, **Tracking**. |
| `Number of Factors` | Number of factors used in study |
| `Factors` | Key input variables (pace, xG, market value, etc.). |
| `Type of Rating` | Dependent variable (player rating, market value, team points, etc.). |
| `Evaluation Metric/Rating System` | e.g., Plus/Minus, VAEP score. |
| `Evaluation Category` | Performance dimension assessed in the paper. |
| `Key Findings` | Concise takeaway reported by the authors. |
| `Criticism/Limitation` | Limitations noted by the authors or identified in our review. |

## Reproducing manuscript figures and tables

1. Clone or download the repository  
   ```bash
   git clone https://github.com/Lchunhang/football-performance-review-data.git
