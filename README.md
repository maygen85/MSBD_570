# MSBD_570
# Malaria Time Series Visualization Comparison

## Project Overview

This project compares different time series visualization techniques for analyzing malaria incidence trends across African countries. The goal is to evaluate which visualization methods most effectively reveal temporal patterns, trends, anomalies, and cross-country differences in malaria incidence data.

The visualization techniques implemented include:

- Line charts
- Small multiples
- Heatmaps
- Horizon charts
- Animated line charts

## Research Question

Which time series visualization technique most effectively reveals temporal patterns and anomalies in malaria incidence data across African countries?

## Dataset

The dataset used in this project is `malaria_Africa_FINAL-Feb25.csv`.

The dataset is compiled from multiple authoritative sources:

- World Health Organization (WHO)
- World Bank Data
- Global Health Observatory (GHO)

### Key Variables

| Variable | Description |
|---|---|
| `Country` | Country name |
| `Year` | Year of observation |
| `malaria_est_incidence` | Estimated malaria incidence |

## Project Structure

```text
project/
│
├── malaria_Africa_FINAL-Feb25.csv
├── malaria_time_series_visualizations.ipynb
├── publication_ready_visualizations.py
├── README.md
│
└── figures/
    ├── 01_line_chart.png
    ├── 02_small_multiples.png
    ├── 03_heatmap.png
    ├── 04_horizon_chart.png
    └── 05_animated_line_chart.gif
