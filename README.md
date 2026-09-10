# Data Analytics on the Net-zero Carbon Goals of Sustainable Cities

## BRICS Carbon Transition – Additional Materials

This repository contains the additional materials required to reproduce the empirical analysis reported in the dissertation:

---

### 1. Project Overview

This study examines carbon-transition patterns in the BRICS countries — Brazil, Russia, India, China, and South Africa — over the period 2000–2024.

The empirical analysis focuses on the relationships between urbanisation, economic growth, and carbon outcomes, as well as the dynamics of growth–emissions decoupling.

The analysis includes:

- Descriptive and trend analysis of carbon and socioeconomic indicators
- Two-way fixed-effects panel regressions
- Diagnostic and robustness tests
- Stationarity tests
- Country-specific trend specifications
- Annual and five-year Tapio decoupling analysis

The materials in this repository are intended to support the reproduction and verification of the empirical results reported in the dissertation.

---

### 2. Data

The analysis uses publicly available data from the World Bank's [World Development Indicators (WDI)](https://datacatalog.worldbank.org/public-licenses#cc-by) for Brazil, Russia, India, China, and South Africa over the period 2000–2024.

The repository provides:

1. The raw WDI export used to construct the analytical dataset.
2. The processed balanced panel dataset used in the empirical analysis.

> **Data License:** Available under the [World Bank Public Data License (CC-BY 4.0)](https://datacatalog.worldbank.org/public-licenses#cc-by).

The data-preparation section of the master notebook filters, reshapes, and processes the source data to construct the balanced country-year panel.

---

### 3. Repository Structure

```text
brics-carbon-transition-additional-materials/
│
├── README.md
│
├── data/
│   ├── WDI_Source_Data.csv
│   └── BRICS_Panel_2000_2024.csv
│
└── code/
    └── BRICS_Carbon_Analysis.ipynb
```

---

### 4. Analytical Structure

| Dissertation Section | Corresponding Notebook Analysis |
| :--- | :--- |
| **Section 4.1** | `Descriptive and trend analysis` |
| **Sections 4.2.1–4.2.2** | `Fixed-effects regression models (M1–M4)` |
| **Section 4.2.3** | `Diagnostic tests, stationarity tests and country-specific trend specifications` |
| **Section 4.3** | `Annual and five-year Tapio decoupling analysis` |
| **Appendix A** | `Detailed diagnostics, stationarity tests and robustness result` |

### Fixed-Effects Specifications

- **M1:** Baseline relationship between urbanisation and total $\text{CO}_2$ emissions
- **M2:** Total $\text{CO}_2$ emissions with real GDP included as an additional explanatory variable
- **M3:** Relationship between urbanisation and $\text{CO}_2$ emissions per capita
- **M4:** Relationship between urbanisation and carbon intensity

Diagnostic and sensitivity analyses are subsequently used to assess the robustness of the estimated relationships.

---

## 5. Reproducibility Notes

Only materials required to reproduce the analyses reported in the dissertation are included in this repository. Temporary code, superseded model specifications, duplicate notebooks and presentation-only outputs are excluded where they are not required for reproduction. The raw WDI dataset and data-preparation code allow the analytical panel to be reconstructed from the source data.

The processed panel dataset is provided separately to facilitate verification of the dataset used in the empirical analysis. The master notebook contains the substantive statistical analysis, robustness checks and decoupling analysis reported in the dissertation. The repository therefore provides the code and data necessary to reproduce the reported empirical results without relying on presentation-only outputs.

---

## Author

- **Student ID:** 14195329  
- **Institution:** The University of Manchester
