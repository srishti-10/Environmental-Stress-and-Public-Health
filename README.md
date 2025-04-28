# Data Visualization Project: Environmental Stress and Public Health

## Overview
This project explores the relationship between environmental quality—specifically **air pollution** and **water quality**—and **public health outcomes** in global cities. The central question is:

> **How do air quality and water pollution levels impact public health in global cities, and what patterns can be identified in their distribution?**

The analysis uses open datasets to examine how environmental stress (via pollution indices and PM2.5 levels) correlates with mortality rates from pollution-related diseases.

---

## Project Structure

```
DataVisualization-SrishtiBinwani/
├── data/
│   ├── Ambient_air_pollution_attributable_death_rate.csv
│   ├── SDGIndicatorConcentrations_of_fine_particulate_matter(PM2.5).csv
│   ├── cities_air_quality_water_pollution.18-10-2021.csv
│   ├── final_dataset.csv
│   ├── health_impact_clean.csv
│   └── pm25_clean.csv
├── notebooks/
│   ├── Final_Analysis_SrishtiBinwani_DataVisualization.ipynb
│   ├── PrimaryAnalysis_SrishtiBinwani_DataVisualization.ipynb
├── analysis_outputs/
│   ├── environmental_stress_histogram.png
│   ├── environmental_stress_vs_mortality.png
│   └── environmental_stress_world_map.png
└── README.md
```

---

## Datasets

### 1. World Cities Air Quality and Water Pollution (2020)
- **Source:** [Numbeo via Kaggle](https://www.kaggle.com/datasets/cityapiio/world-cities-air-quality-and-water-polution)
- **Description:**
  - Observations from nearly 4,000 global cities
  - **Air Quality Index (AQI):** 0 = worst, 100 = best
  - **Water Pollution Index:** 0 = clean, 100 = heavily polluted
  - 3,963 cities, 177 countries, 1,153 regions
  - Licensed under *CC0: Public Domain*

### 2. SDG Indicator 11.6.2 – PM2.5 Concentrations
- **Source:** [UN SDG Indicators Database](https://unstats.un.org/sdgs/indicators/database/)
- **Description:**
  - Annual mean concentrations of PM2.5 (2019)
  - Data by country and major cities

### 3. Ambient Air Pollution Attributable Death Rate
- **Source:** WHO
- **Description:**
  - Mortality rates attributable to air pollution (by country)

---

## Notebooks
- **Final_Analysis_SrishtiBinwani_DataVisualization.ipynb**: Integrates all datasets, performs advanced analysis, and generates final visualizations.
- **PrimaryAnalysis_SrishtiBinwani_DataVisualization.ipynb**: Initial data cleaning, exploration, and basic visualizations.
- **untitled.txt**: Notes, open data concepts, and brainstorming.

## Analysis Outputs
- **environmental_stress_histogram.png**: Histogram of environmental stress scores.
- **environmental_stress_vs_mortality.png**: Scatter/line plot showing relationship between stress and mortality.
- **environmental_stress_world_map.png**: World map visualization of environmental stress.

---

## Key Findings
- There is a **statistically significant positive correlation** between environmental stress (pollution indices, PM2.5) and mortality from pollution-related diseases (COPD, heart disease, lung cancer).
- The correlation holds across different levels of economic development.
- Environmental stress is **geographically uneven**, with higher stress and mortality in the Global South and lower-income regions.
- Policy implication: **Environmental policy is health policy**—investments in clean air and water are essential for reducing preventable deaths.

---

## How to Use
1. **Open the Notebooks** in Jupyter or VSCode to explore the analysis step by step.
2. **Run the code cells** to reproduce data cleaning, merging, and visualization.
3. **Examine the PNG outputs** for quick insights into key findings.

---

## Requirements
- Python 3.7+
- pandas
- matplotlib
- seaborn
- geopandas

Install dependencies with:
```bash
pip install pandas matplotlib seaborn geopandas
```

---

## References
- Landrigan, P. J., et al. (2018). *The Lancet Commission on pollution and health.* [The Lancet, 391(10119), 462–512.](https://doi.org/10.1016/S0140-6736(17)32345-0)
- [UNEP (2021) - Making Peace with Nature](https://www.unep.org/resources/making-peace-nature)
- [Numbeo Air Quality and Water Pollution Dataset](https://www.kaggle.com/datasets/cityapiio/world-cities-air-quality-and-water-polution)
- [UN SDG Indicators Database](https://unstats.un.org/sdgs/indicators/database/)
- WHO Global Health Observatory

---

## Author
Srishti Binwani

---