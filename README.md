# Solar Panel Performance Analysis

A data analysis project examining solar generation performance 
across two plants using real-world SCADA data. Built with Python, 
Pandas, Scikit-Learn, and Seaborn.

---

## Key findings

- **Plant 1 outperforms Plant 2 by ~30%** in total energy output 
  over the analysis period (May 17 – Jun 17, 2020)
- **7.5% anomaly rate** detected across inverters, with likely 
  causes including panel soiling, inverter faults, shading, 
  and thermal clipping
- **Peak generation occurs at 12:00 PM**, averaging 808 kWh 
  across both sites
- Irradiation and module temperature are the strongest 
  predictors of AC power output

---

## Project structure

| File | Description |
|------|-------------|
| `Solar_Performance_Data_Script.ipynb` | Main analysis notebook |
| `Plant_1_Generation_Data.csv` | Generation data — Plant 1 |
| `Plant_1_Weather_Sensor_Data.csv` | Weather sensor data — Plant 1 |
| `Plant_2_Generation_Data.csv` | Generation data — Plant 2 |
| `Plant_2_Weather_Sensor_Data.csv` | Weather sensor data — Plant 2 |

---

## Tools used

- **Python** — Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
- **Analysis** — Anomaly detection (Z-score), linear regression, 
  time-series EDA
- **Visualization** — Seaborn whitegrid charts, correlation heatmaps

---

## How to run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook Solar_Performance_Data_Script.ipynb
```

---

## About

Built as part of a portfolio project to demonstrate data analysis 
skills in the renewable energy sector. Dataset sourced from 
[Kaggle — Solar Power Generation Data]
(https://www.kaggle.com/datasets/anikannal/solar-power-generation-data).
