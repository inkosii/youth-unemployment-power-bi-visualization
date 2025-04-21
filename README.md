# 🇿🇦 South African Youth Unemployment Analysis

This project explores the **youth unemployment trends in South Africa** using data from **ILOSTAT**. The focus is on the age group **15–24**, and the final insights are visualized in **Power BI**.

---

## Goal

To clean, analyze, and visualize youth unemployment in South Africa — and understand how unemployment rates vary across **gender and time**.

---

## Data Source

- **Source**: [ILOSTAT](https://ilostat.ilo.org/)
- **Dataset**: Unemployment rate by country, source, age group, gender, and year.
- **Subset Used**: Only data for **South Africa**, filtered to include **Youth (15–24)**.

---

## ⚙️ Tools & Technologies

- Google Colab (Python / Pandas for data cleaning & EDA)
- Power BI (for storytelling & interactive visuals)
- GitHub (project hosting & documentation)

---

## Data Cleaning Highlights

- Filtered for `ref_area.label = South Africa`
- Filtered `classif1.label = Age (Youth, adults): 15–24`
- Encoded gender labels (`0 = Female`, `1 = Male`, `2 = Total`)
- Converted time to datetime and created year columns
- Dropped unused columns with heavy missing values

---

## Power BI Visuals

- **Line Chart**: Gender-based trends from 2000–2024
- **Card**: To depict the unemployment rate average
- **Decomposition Tre**: To breakdown, and get a detailed insights on the factors that influence unemployment, by year and gender
- **Tooltips**: Custom insights when hovering on visuals

---

## Insights

- Youth unemployment in South Africa remains **consistently high**, especially among **females**.
- The unemployment rate spiked after **2020**, potentially reflecting economic challenges due to COVID-19.
- Gender disparity is visible — with females often reporting **higher unemployment rates**.

---

## Contact / Feedback

Feel free to fork the repo, raise issues, or any suggestions!

---
