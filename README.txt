# Data and scripts for  
“A Systematic Review of Modern Football Performance Measures (2018 – 2024)”

This repository contains the research data and companion materials that support the findings of the review paper:

> **Lee C. H., Mohamad A. H., Asirvatham D.**  
> *A Systematic Review of Modern Football Performance Measures (2018 – 2024).*  
> Submitted to the ACML 2025 collection, **Machine Learning** (Springer).

## Contents

| File | Description |
|---|---|
| **A Systematic Review of Modern Football Performance Measures REVIEW SHEET.csv** | UTF-8 CSV with coded information for the **74** included studies, now with **Study Design** labels (D/X/P/R) and data-modality badges (A/E/T/H). |
| **search_strings.txt** | Exact Scopus, ScienceDirect, and SAGE queries used in the PRISMA search (2018–2024; English). |

---

## Study-design & data-modality schema

- **Study design (D/X/P/R)**  
  - **Descriptive:** summaries/associations without predictive validation.  
  - **Explanatory:** regression/associational models emphasising coefficients/effect sizes.  
  - **Predictive:** supervised models reporting out-of-sample metrics (e.g., MAE/RMSE/R², AUC, Brier/log-loss; hold-out/temporal CV).  
  - **Algorithmic rating/composite:** rule-based or learned indices/ratings (e.g., plus–minus, VAEP, PlayeRank, fuzzy/MCDM composites).
---

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
| `Study Design` | Long label: Descriptive / Explanatory / Predictive / Algorithmic rating/composite. |
| `Key Findings` | Concise takeaway reported by the authors. |
| `Criticism/Limitation` | Limitations noted by the authors or identified in our review. |


