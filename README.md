# EV Charger Utilisation & Efficiency Analysis (Project 03)

## Overview
An end-to-end data analytics and Power BI dashboard project analysing 30-day hourly EV charger utilisation, idle time, evening peak-load demand (18:00–22:00), and station bottlenecks to guide infrastructure optimisation.

## Key Metrics & Findings
- **Average Utilisation Rate:** 54.32% across stations
- **Average Idle Time:** 27.41 mins/hr
- **Total Energy Delivered:** 103.24K kWh
- **Total Bottleneck Hours:** 2,000+ hours concentrated during evening peak windows (18:00–22:00)

## Tools & Technologies
- **Python (Pandas, NumPy, Matplotlib, Seaborn):** Data cleaning, hourly feature engineering, utilisation calculations, and peak-load modelling
- **Power BI:** Interactive executive dashboard featuring KPI cards, a station-by-hour utilisation heatmap matrix, hourly peak-load column chart, and station ranking bars

## Repository Files
- `charger_utilisation_analysis.ipynb` — Jupyter Notebook for data preparation, utilisation modelling, and CSV exports
- `Task 3.pbix` — Interactive Power BI report
- `charger_hourly_utilisation.csv` — Hourly utilisation and idle metrics by charger/station
- `charger_performance_ranking.csv` — Charger-level performance and ranking summary
- `hourly_peak_load.csv` — Aggregated hourly energy and load trends
- `station_utilisation_summary.csv` — Station-level utilisation and bottleneck summary

## Capacity Optimisation Recommendations
1. **Expand High-Bottleneck Stations:** Prioritize additional fast-charging bays at top-ranked stations experiencing sustained congestion during the 18:00–22:00 peak window.
2. **Reduce Post-Charge Idle Time:** Introduce grace-period alerts or overstay idle fees where average idle duration approaches 27+ mins/hr.
3. **Shift Fleet & Commercial Loads:** Offer off-peak tariff incentives (00:00–06:00) for fleet and delivery vehicles to balance grid load and boost low-utilisation hours.
