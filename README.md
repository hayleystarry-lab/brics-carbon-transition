**Data Analytics on the Net-zero Carbon Goals of Sustainable Cities**

# BRICS Carbon Transition – Additional Materials

This repository contains the additional materials required to reproduce the empirical analysis reported in the dissertation:

---

## 1. Project Overview

This study examines carbon-transition patterns in the BRICS countries — Brazil, Russia, India, China and South Africa — over the period 2000–2024.

The empirical analysis focuses on the relationships between urbanisation, economic growth and carbon outcomes, as well as the dynamics of growth–emissions decoupling.

The analysis includes:

- descriptive and trend analysis of carbon and socioeconomic indicators;
- two-way fixed-effects panel regressions;
- diagnostic and robustness tests;
- stationarity tests;
- country-specific trend specifications; and
- annual and five-year Tapio decoupling analysis.

The materials in this repository are intended to support the reproduction and verification of the empirical results reported in the dissertation.

---

## 2. Data

The analysis uses publicly available data from the World Bank's **World Development Indicators (WDI)** for Brazil, Russia, India, China and South Africa over the period 2000–2024.

The repository provides:

1. the raw WDI export used to construct the analytical dataset; and
2. the processed balanced panel dataset used in the empirical analysis.

The World Bank data are available under the World Bank's public data licence:

https://datacatalog.worldbank.org/public-licenses#cc-by

The data-preparation section of the master notebook filters, reshapes and processes the source data to construct the balanced country-year panel.

---

## 3. Repository Structure

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
