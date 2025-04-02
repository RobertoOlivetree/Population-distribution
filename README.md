# 🏙️ Population Distribution in Buildings Based on BGRI Data

This repository contains scripts and data files for estimating and visualizing the distribution of the elderly population (65+) in buildings, based on BGRI statistical subsections in Porto, Portugal. The project uses Python libraries such as GeoPandas, Folium, and OSMnx for spatial analysis and visualization.

---

## 📌 Project Overview

The goal of this project is to:

- Analyze the spatial distribution of the elderly population (65+) in buildings.
- Compute population estimates per building using BGRI statistical data.
- Distribute the population proportionally to building footprint area.
- Generate an interactive **Folium** map showing the estimated 65+ population per building.

---

## 📂 Files in this Repository

| File                      | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| `BGRI2021_1312.gpkg`      | GeoPackage containing BGRI statistical zones for Porto.                     |
| `edificios.csv`           | CSV file with building data, including geometries in WKT format.            |
| `population_distribution.ipynb` | Jupyter Notebook performing the population allocation and visualization. |

---

## 🛠️ Setup & Dependencies

To run the notebook, you’ll need to install the following Python packages:

```bash
pip install pandas geopandas osmnx folium networkx shapely joblib matplotlib numpy

