# Change Point Analysis and Statistical Modeling (Brent Oil)

This repository contains a Week 11 project analyzing how major geopolitical/economic events relate to structural breaks (change points) in Brent oil prices.

## Project structure

- `data/raw/` – raw data (Brent oil prices + curated events)
- `notebooks/` – EDA + Bayesian change point notebooks
- `src/` – reusable Python utilities
- `models/` – exported model outputs (JSON/CSV)
- `reports/figures/` – figures used for interpretation/dashboard

## Quick start

1) Create an environment and install dependencies:

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

2) Open and run notebooks in `notebooks/`.

## Dashboard (Task 3)

The dashboard will live under `dashboard/` (Flask backend + React frontend) with instructions added when implemented.
