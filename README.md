# 📉 Declining Births & Early Childhood Education in Chile

**Demographic and educational analysis | Maule Region · National scope**  
*R · Python · Power BI · 2026*

---

## Overview

Chile is experiencing a sustained decline in birth rates with direct consequences 
for the early childhood education system. This project analyzes birth registration 
trends and early childhood enrollment data to understand the magnitude of the 
phenomenon, its territorial distribution, and its projected impact on educational 
demand through 2030.

The analysis combines official data from multiple sources and progresses from 
regional diagnosis to national predictive modeling.

---

## Key finding

> The Maule region registered **33% fewer births in 2025 than in 2018** — equivalent 
> to 350 fewer children per month. If the current trend holds, early childhood 
> enrollment demand could fall below 7,500 annual cases by 2027.

---

## Data sources

| Source | Dataset | Period |
|--------|---------|--------|
| Registro Civil de Chile | Birth registrations by municipality | 2018–2025 |
| MINEDUC | Early childhood enrollment (national) | 2012–2025 |
| INE / UN | Birth rate indicators | 2018–2025 |

*Birth registration data obtained via Transparency Law request — Folio AK002T0036701*

---

## Project structure
```
proyecto-natalidad/
│
├── data/              # Raw and processed datasets
├── scripts/           # R and Python analysis scripts  
├── outputs/           # Visualizations and model results
└── docs/              # Reports and documentation
```

## Analysis roadmap

- [x] **Phase 1 — Regional diagnosis:** Exploratory analysis of birth registrations
      in Maule region (2018–2025). Temporal trends, territorial breakdown,
      seasonality patterns.
- [ ] **Phase 2 — National analysis:** Cross-analysis of national enrollment data
      with birth rate trends. Rural/urban comparison across regions.
- [ ] **Phase 3 — Predictive model:** Enrollment demand projections for 2026–2030
      based on demographic indicators.
- [ ] **Phase 4 — Dashboard:** Strategic Power BI dashboard for decision-makers
      in early childhood education policy.

---

## Phase 1 — Key results (Maule Region)

| Indicator | Value |
|-----------|-------|
| Total births registered (2018) | 12,594 |
| Total births registered (2025) | 8,400 |
| Cumulative decline | -33.3% |
| Peak single-year drop | -10.9% (2023→2024) |
| Most affected locality | Parral (-78.7%) |
| Partial recovery observed | Curicó (+5.6% in 2024–2025) |

📄 [Full descriptive report (Phase 1) →](./docs/Informe_Nacimientos_Maule_2018_2025.docx)

---

## About the author

**Hugo Méndez** — Data analyst specializing in education and early childhood development.  
9 years of experience in educational organizations · MSc Human Resources Management  
📧 hugomendez.data@gmail.com · 🔗 [LinkedIn](https://linkedin.com/in/hugomendez-data) · 
🗂️ [Portfolio](https://github.com/hmendezdata/portfolio)
