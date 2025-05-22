# California ER Utilization Analysis (2018–2023)

This project analyzes five years of emergency room (ER) visit data across 300+ hospitals in California to uncover healthcare service trends, payer shifts, and diagnosis patterns during and after the COVID-19 pandemic.

---

## 📊 Objective

* Understand shifts in ER utilization across diagnosis categories, insurance types, and patient dispositions.
* Detect patterns related to mental health visits, mortality rates, and county-level demand.

---

## 🧰 Tools & Technologies

* **SQL (BigQuery)**: Querying and aggregating multi-year data
* **Pandas**: Data cleaning, merging, and KPI feature engineering
* **Tableau**: Interactive visualizations for stakeholders

---

## 🗂️ Data Sources

* Annual ER summary files (2018–2023) from OSHPD/CalHHS
* Pivot instructions file for field mapping and data validation

---

## 🧮 Key KPIs & Features Engineered

* `mortality_rate` = ER deaths ÷ total ER visits
* `mental_health_rate` = Mental health visits ÷ total ER visits
* Payer type distributions: Medi-Cal, Medicare, Private, Self-pay
* Disposition outcome ratios: Admitted, Died, Left AMA

---

## 📈 Dashboard Insights

* **Visit Volume Trends**: Monthly and yearly ER usage patterns
* **Insurance Mix**: Shifts in coverage post-COVID
* **Mental Health Surges**: Peaks in 2020 and 2021 visualized by age/county
* **Disposition Trends**: Increase in ER-to-hospital admissions

---

## 📍 Project Structure

```
📁 data/
├── 2018-data.csv
├── 2019-data.csv
├── ...
├── 2023-data.csv
└── 2019-ed-pivot-table_20201013.xlsm

📁 notebooks/
└── er_data_analysis.ipynb

📁 dashboards/
└── tableau_dashboard.twbx

📄 README.md
```

---

## ✅ Outcome

Enabled public health stakeholders to quantify pandemic-driven demand surges, payer shifts, and mental health trends, aiding resource allocation and healthcare access planning.

---

## 👩‍💻 Author

**Aishwariya Alagesan**
[LinkedIn](https://www.linkedin.com/in/aishwariya-alagesan) | [Portfolio](https://public.tableau.com/app/profile/aishwariya.alagesan)
