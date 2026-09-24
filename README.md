# 🦠 COVID-19 Analysis Dashboard (Tableau)

## 📌 Overview

An interactive Tableau dashboard exploring COVID-19 cases, deaths, and risk factors — analyzing how age, sex, and pre-existing conditions (like pneumonia) relate to death outcomes, alongside the monthly trend of recorded deaths.

---

## 🎯 Business Objective

Public health teams need a quick way to spot which population groups carry the highest risk. This dashboard answers:

- What is the overall case count, death count, and recovery rate?
- Which age group has the highest death rate?
- Is there a difference in case counts or outcomes by sex?
- How strongly is pneumonia linked to death?
- How did deaths trend month over month?

---

## 🗂 Dataset

- Source file: `Covid_Data_csv.xlsx`
- Patient-level records including age, sex, death date/status, and pneumonia status
- Aggregated in the dashboard into age groups (0–18, 19–30, 31–45, 46–60, 61+)

---

## 🛠 Tools Used

- Tableau Desktop (data modeling, calculated fields, dashboard design)
- Excel (source data)

---

## 📈 Dashboard Features

- **Filters:** Sex Group, Age Group, Death Date range
- **KPI cards:** Total Cases, Total Deaths, Recovery Rate, Pneumonia Rate
- **Death Rate by Age Group** — bar chart showing risk increases sharply with age
- **COVID Cases by Age Group** — case volume distribution across age bands
- **COVID Cases by Sex** — male vs. female case share
- **Death Trend** — monthly record count over the year
- **Pneumonia Death Heatmap** — cross-tab of pneumonia status vs. death outcome

---

## 📊 Key KPIs

| KPI | Value |
|---|---|
| Total Cases | 391,979 |
| Total Deaths | 76,942 |
| Recovery Rate | 19.63% |
| Pneumonia Rate | 13.56% |

**Key insight:** Death rate rises sharply with age — from ~7% in the 0–18 group to **58.19%** in the 61+ group, making age the strongest single risk factor in this dataset.

---

## 🖼 Dashboard Preview

![COVID-19 Analysis Dashboard](./screenshots/dashboard_screenshot.png)

---

## 📂 Project Files

- `COVID_data.twb` — Tableau workbook (open with Tableau Desktop or Tableau Public)
- `/data/Covid_Data_csv.xlsx` — source dataset
- `/screenshots/dashboard_screenshot.png` — dashboard preview image

---

## 🚀 Author

**Ashish Kumar**
Data Analyst | Power BI | Tableau | SQL | Python | Excel
