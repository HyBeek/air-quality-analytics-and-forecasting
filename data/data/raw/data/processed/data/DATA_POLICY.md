# Data Strategy & Governance Policy

## Overview
This project analyzes and forecasts PM2.5 air pollution data using publicly
available environmental datasets. To ensure reproducibility and ethical data
handling, strict data governance rules are enforced.

## Data Sources
- OpenAQ: Global air quality measurements (PM2.5)
- Meteorological datasets for contextual analysis

## Data Storage Policy
- Raw data is stored locally in `data/raw/`
- Processed data is stored locally in `data/processed/`
- External reference data is stored locally in `data/external/`

These directories are intentionally excluded from version control.

## Version Control Rules
- No datasets are committed to GitHub
- Only code, notebooks, and documentation are versioned
- All data ingestion is reproducible via scripts or notebooks

## Reproducibility
Anyone cloning this repository can reproduce results by:
1. Installing dependencies
2. Running data ingestion notebooks
3. Executing analysis notebooks in sequence
