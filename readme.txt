# Pressure Quotient: IPL Toss Impact & Match Strategy Analysis (2008–2026)

An end-to-end data analytics and behavioral economics project exploring IPL match data, toss psychology, and strategic decision-making trends under pressure.

---

## 📌 Project Overview
Why do the vast majority of modern T20 captains choose to field first, and how has toss strategy evolved since the inception of the IPL in 2008? This project analyzes historical data across **1,212+ matches** to uncover patterns in toss decisions, win percentages, and team strategies.

---

## 🛠️ Tech Stack & Tools
* **Data Processing & Cleaning:** Python (Pandas, Jupyter Notebooks)
* **Data Transformation:** Power Query, Custom ID-to-Name Mapping Pipelines
* **Data Modeling & Calculations:** DAX Measures
* **Data Visualization & Dashboard:** Power BI
* **Version Control:** Git & GitHub

---

## 📊 Dashboard Features & Key Insights
The interactive Power BI dashboard is structured into comprehensive analytical views:
1. **Team-Wise Toss & Win Performance (Page 1):** Tracks total matches played, total wins, and toss win percentages across distinct historical franchises (preserving unique entries like Gujarat Lions vs. Gujarat Titans).
2. **Toss Decision Evolution Across Seasons (Page 2):** Highlights the massive strategic shift in T20 cricket—transitioning from a heavy preference for batting first in the early seasons (2008–2013) to an overwhelming dominance of fielding/chasing in modern seasons.
3. **In-Progress Integration:** Incorporates structured partial-season tracking for active fixtures (such as the 2026 season data pipeline).

---

## 📂 Repository Structure
```text
Pressure-Quotient-IPL/
│
├── dashboard/        # Power BI (.pbix) report files
├── data/             # Raw and processed datasets (CSV)
├── notebooks/        # Jupyter notebooks for data cleaning & Python scripts
├── outputs/          # Exported charts and analysis visual assets
└── requirements.txt  # Python dependencies
