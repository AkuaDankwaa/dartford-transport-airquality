# 📍 Transport Accessibility and Air Quality Analysis – Dartford, Kent

## Overview
This project explores **public transport accessibility and proximity to major road networks in Dartford, Kent**, using openly available UK datasets and geospatial analysis techniques. The aim is to demonstrate how transport and environmental data can be prepared, analysed, and visualised to support discussions around **sustainable transport, accessibility, and local planning**.

The project is developed incrementally, following best practices in **GIS, data processing, and reproducible analysis**.

---

## Project Objectives
- Prepare and clean official UK transport and geographic datasets  
- Analyse the spatial distribution of bus stops within Dartford  
- Establish a reproducible workflow for transport accessibility analysis  
- Lay the groundwork for future analysis of environmental exposure and inequality  

---

## Data Sources
All datasets used in this project are **publicly available UK sources**:

- **Dartford Local Authority Boundary**  
  Source: ONS Open Geography Portal  

- **Bus Stop Locations (NaPTAN)**  
  Source: UK Department for Transport – National Public Transport Access Nodes  

Additional datasets (e.g. road networks, deprivation indices) may be incorporated in later stages.

---

## Repository Structure

## Repository Structure

    dartford-transport-airquality/
    │
    ├── notebooks/
    │   └── 01_project_setup_and_data_exploration.ipynb
    │
    ├── data/
    │   ├── raw/
    │   │   └── dartford_boundary.geojson
    │   └── processed/
    │       └── bus_stops_dartford_clean.geojson
    │
    └── README.md



---

## Current Progress
✔ Loaded and validated the Dartford local authority boundary  
✔ Assigned missing CRS metadata (EPSG:4326)  
✔ Loaded and filtered NaPTAN bus stop data  
✔ Spatially clipped bus stops to Dartford  
✔ Reduced dataset to essential attributes  
✔ Produced exploratory visualisations  
✔ Saved processed datasets for reuse  

All analysis steps and outputs are documented in the Jupyter notebook.

---

## Tools & Technologies
- Python (Pandas, GeoPandas, Shapely, Matplotlib)  
- Jupyter Notebooks  
- OpenStreetMap & UK Government open data  
- GitHub for version control and documentation  

---

## Next Steps
Planned next stages of the project include:
- Transport accessibility analysis using distance-based buffers  
- Integration of road network data as a proxy for air quality exposure  
- Aggregation of results at neighbourhood (LSOA) level  
- Clear visual outputs to support planning and policy discussions  

---

## Notes
This project is intended as a **demonstration of applied geospatial and transport analysis** using UK public-sector data. It does not make health impact claims and should be interpreted as exploratory and illustrative.

---

## Author
**Dankwaa Akua Yeboah**  
Graduate Transport & Geospatial Analyst  
GitHub: https://github.com/AkuaDankwaa
