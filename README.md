🏙️ Population Distribution in Buildings Based on BGRI Data

This repository contains scripts and data files for estimating and visualizing the elderly population (65+) distribution in buildings based on BGRI statistical subsections in Porto, Portugal. The project utilizes Python, GeoPandas, Folium, and OSMnx for spatial analysis and visualization.
📌 Project Overview

The goal of this project is to:

    Analyze the spatial distribution of the elderly population (65+) in buildings.
    Compute population estimates per building based on BGRI statistical data.
    Distribute the population proportionally to building areas.
    Generate an interactive Folium map showing population density per building.

📂 Files in this Repository
File 	Description
BGRI2021_1312.gpkg 	GeoPackage containing BGRI statistical zones for Porto.
edificios.csv 	CSV file with building locations and geometries (WKT format).
population_distribution.ipynb 	Jupyter Notebook calculating the 65+ population distribution in buildings.
🛠️ Setup & Dependencies

To run the Jupyter notebooks, install the necessary dependencies:

pip install pandas geopandas osmnx folium networkx shapely joblib matplotlib numpy
