# Safe, Clean, or Cheap? — Indian City Liveability EDA

Exploratory data analysis across 21 Indian cities combining safety, sanitation, and economic data into a single composite liveability score.

## Datasets
- **Swachh Survekshan** — cleanliness scores (2016–2023)
- **NCRB** — city-level crime incidents
- **Numbeo** — cost of living, rent, salary

## What I Did
- Cleaned and merged 3 independent datasets
- Engineered features: `crime_per_income`, `income_after_rent`
- Built a normalized composite score using min-max scaling across 4 dimensions
- Visualized relationships between cost, crime, and cleanliness

## Key Findings
- Varanasi and Nashik rank safer than most metros by crime count
- Surat is India's cleanliness leader but has a brutal rent-to-income ratio
- No strong relationship found between city cost and crime rate
- Mumbai: high cost, high crime, negative disposable income

## Limitations
- 21 cities only — limited by dataset overlap
- Crime not normalized by population
- Equal weights across dimensions — subjective

## Stack
Python · pandas · numpy · matplotlib · seaborn

---
*First end-to-end data project — built on real, messy, multi-source data.*
