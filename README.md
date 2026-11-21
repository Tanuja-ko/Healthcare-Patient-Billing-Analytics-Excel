# Healthcare Patient & Billing Analytics (Microsoft Excel)

Exploratory data analysis and billing segmentation of **10,000 hospital patient records (2018–2023)** in **Microsoft Excel**.

## Data Cleaning & Preparation
* **Category Standardization:** Normalized inconsistent text casing and expanded truncated admission labels (`Emer` → `Emergency`).
* **Billing & Schema Cleanup:** Resolved alphanumeric typos in billing records, standardized currency formatting, and removed **11 empty columns**.
* **Age Cohort Engineering:** Grouped patient ages into four brackets (`18–29`, `30–44`, `45–59`, `60+`) for demographic comparison.

## Key Findings (8 Pivot Table Views)
* **Top Diagnosis:** **Hypertension** is the most common condition, representing **21.55%** of total admissions.
* **Age Distribution:** Patients aged **60+** make up **38.13%** of all encounters.
* **Admission Type:** **Emergency** visits account for **35.87%** of total volume.
* **Billing Comparison:** **Cancer ($39,688)** and **Diabetes ($30,097)** generate **~3x higher average billing** per visit than **Obesity ($12,512)**.

## Repository Contents
* **`Healthcare_Data_Analysis.xlsx`** — Raw dataset (`Healthcare_Raw`), cleaned dataset (`Healthcare_Cleaned`), and 8 Pivot Table sheets (`01_Demographic_Analysis` through `07_Admission_Trends` plus `Admission Type Analysis`).
