# Dataset Analysis — Asthma Disease

Exploratory data analysis for an asthma diagnosis dataset (Kaggle). Part of an ML pipeline for a clinic-style use case (**BreathWell Clinic**).

## What this lab covers

- Dataset overview: shape, dtypes, descriptive stats, target distribution
- Data quality: missing values, outliers (IQR), duplicates
- Loading data into **PostgreSQL** (`asthma_patients_data`)
- Interactive visuals with **Plotly** (age, BMI, environment, lifestyle vs diagnosis)
- Short conclusions for the business / medical context

## Stack

`Python` · `pandas` · `numpy` · `matplotlib` · `seaborn` · `plotly` · `SQLAlchemy` · `PostgreSQL`

## How to run

1. Place `asthma_disease_data.csv` next to the notebook (or update the path in the cells).
2. Configure PostgreSQL connection in the notebook (prefer env vars, do not commit passwords).
3. Open and run `lab1.ipynb` top to bottom.

## Project structure

```
dataset-analysis/
├── lab1.ipynb
└── README.md
```

