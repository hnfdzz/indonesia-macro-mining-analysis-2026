## Macroeconomic & Labor Impact Analysis: Indonesia's Mining Sector (2026)

This repository contains a Python-based data analysis project exploring the causal relationship between domestic monetary tightening policies, mining commodity export performance, and their subsequent impact on labor stability in Indonesia during 2026.

## Background & Problem Statement
Throughout 2026, a significant macroeconomic shift occurred as consecutive increases in Bank Indonesia's benchmark interest rate (BI-Rate) led to systematic liquidity tightening. This project aims to map how this aggressive monetary tightening correlates with a downturn in mining export volumes, and to estimate the scale of the resulting social impact—specifically the wave of workforce layoffs (PHK) across national smelters and industrial hubs.

## Tech Stack & Libraries
* **Language:** Python 3.13+
* **Data Manipulation:** Pandas
* **Data Visualization:** Matplotlib, Seaborn
* **Environment Manager:** Virtual Environment (`.venv`)

## Repository Structure
```text
Project Analisis Data/
├── .venv/                  # Virtual Environment
├── data/                   # Cleaned CSV datasets (Macro & Labor)
│   ├── data_dampak_phk.csv
│   └── data_makro.csv
├── src/
│   └── analisis.ipynb      # Jupyter Notebook (Analysis & Visualization Pipeline)
├── plot1_bi_rate_vs_ekspor.png
├── plot2_krisis_phk.png
└── README.md
