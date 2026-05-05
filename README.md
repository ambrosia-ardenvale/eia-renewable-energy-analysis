# eia-renewable-energy-analysis
# U.S. Renewable Energy Time Series Analysis
### Solar, Wind & Hydroelectric Power | EIA Data 1973–2025

**BUS 267 | Ambrosia Ardenvale-Wood | March 2026**

---

## The Bottom Line

Using 50+ years of monthly EIA data, this project builds a predictive regression model for total U.S. renewable energy consumption, and demonstrates that **temporal patterns alone can explain 88% of variance** in output across solar, wind, and hydroelectric sources.

The model surfaces a concrete, data-driven investment insight: **the September–October trough is not a generation problem. It indicates lack of sufficient energy storage.**

---

## Project Assets

| Asset | Description |
|-------|-------------|
| [`EIA_energy_proj_final.ipynb`](./EIA_energy_proj_final.ipynb) | Full analysis notebook (Python) |
| [`BUS_267_Final_Project_Slides.pdf`](./BUS_267_Final_Project_Slides.pdf) | Presentation slide deck |
| [▶ Watch the Presentation](https://youtu.be/nH1aiG6tzCk) | Recorded walkthrough with full narration |

---

## Key Findings

- **R² = 0.88** Regression model using Year, Season, and Month as features
- **MAE = 19.49 Trillion Btu**
- **June** is the single strongest monthly driver (+11.35 coefficient)
- **Spring Seasonal Growth Factor = +0.61** Spring peaks are intensifying year over year as installed capacity expands
- **September & October** carry the largest negative coefficients (−8.94 and −8.53), marking a quantifiable and predictable annual trough

---

## The Storage Insight

The Sept–Oct intermittency gap sits between solar's summer peak and wind's winter increase. More generating capacity in October could temporarily bandaid the problem, but **better storage for July's energy production provides a stable and reliable remedy.** Battery and pumped hydro solutions sized specifically for this gap represent the most actionable immediate investment opportunity in the U.S. renewable portfolio.

---

## Data Source

**EIA Monthly Energy Review, Table 10.1**
- 634 monthly observations (1973–2025)
- Sources: Solar, Wind, Hydroelectric
- Early-year zeros for solar and wind reflect the absence of utility-scale infrastructure: a deliberate, conservative modeling choice

---

## Technical Stack

```
Python · Pandas · NumPy · Scikit-learn · Matplotlib · Seaborn
Linear Regression with polynomial & interaction terms
Feature engineering: Season, Year, Total Renewables, temporal interaction terms
```

---

## Business Recommendations

1. **Strategic Capacity Planning** Schedule major maintenance in late autumn to maximize asset availability during the spring and summer high-performance window
2. **Storage Investment** *(Featured)* Target battery and pumped hydro solutions sized to bridge the Sept–Oct trough and capture July generation surplus
3. **Model Implementation** R² of 0.88 makes this model viable as a secondary validation tool for 12-month budgetary forecasting

---

## About

Completed as a capstone analytics project at Shoreline Community College while pursuing an AASc in Business Intelligence & Data Analytics. Built with a sustainability and mission-driven lens. This analysis is exactly the type of work I desire to spearhead in the future.

📫 [LinkedIn](https://linkedin.com/in/ambrosiaardenvalewood) · ardenvale.ambrosia@gmail.com
