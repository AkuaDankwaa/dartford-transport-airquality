# Dartford Transport and Air Quality Analysis

## Project Overview
This project analyses **public transport accessibility** and **air quality exposure** in **Dartford, Kent**, using geographic data science techniques. The aim is to identify spatial inequalities that are relevant to **local transport planning, environmental policy, and public-sector decision-making**.

The project demonstrates how **open data, GIS analysis, and cloud-based tools** can be used to generate accessible, policy-relevant insights for UK towns.

---

## Why Dartford?
Dartford sits at the intersection of major transport corridors, including the **A2, M25, and Dartford Crossing**. While this connectivity supports economic activity, it also raises challenges related to **traffic congestion, air pollution, and unequal access to public transport**.

This project focuses on Dartford to:
- Explore the local impacts of transport infrastructure
- Highlight place-based inequalities often hidden in national datasets
- Demonstrate how data can support evidence-informed local decision-making

---

## Problem Statement
Access to reliable public transport and exposure to air pollution are closely linked to **social and environmental inequality**. These factors are often analysed separately, making it harder to understand where risks overlap.

This project asks:
> Which areas of Dartford experience lower public transport accessibility and higher potential exposure to traffic-related air pollution, and how do these patterns relate to deprivation?

The goal is not to make medical claims, but to provide **spatial insight** that can inform transport, environmental, and planning discussions.

---

## Data Sources
All datasets used are publicly available UK sources, including:
- **Public transport stops** (NaPTAN / OpenStreetMap)
- **Road network data** (OpenStreetMap, used as a proxy for traffic-related emissions)
- **Index of Multiple Deprivation (IMD)** at Lower Super Output Area (LSOA) level

Data cleaning steps and assumptions are documented in the analysis notebooks.

---

## Technical Approach
The project follows a GIS-based analytical workflow:
1. Mapping public transport stop locations across Dartford
2. Estimating walkable access to bus stops using buffer analysis
3. Analysing proximity to major roads as a proxy for air quality exposure
4. Spatially joining results with deprivation data
5. Visualising findings using interactive maps and charts

The emphasis is on **transparent, reproducible analysis** rather than complex modelling.

---

## Tools & Technologies
- Python (pandas, geopandas)
- Geographic Information Systems (GIS)
- Interactive mapping and visualisation
- Cloud deployment using AWS
- Version control with GitHub

---

## Outputs
Planned outputs include:
- Interactive maps showing transport accessibility and road proximity
- Choropleth maps of deprivation across Dartford
- Summary charts highlighting spatial patterns
- A publicly accessible web dashboard

Screenshots and a live demo link will be added as the project progresses.

---

## Public Impact
This project is designed to support:
- Local authorities exploring transport equity
- Civic tech and urban data initiatives
- Environmental and planning teams interested in spatial risk factors
- Community stakeholders seeking accessible data insights

The analytical framework can be adapted for other UK towns and cities.

---

## Project Status
🚧 In progress  
Current focus: data processing, spatial analysis, and dashboard development.

---

## About the Author
I am a **Geographic Data Science MSc graduate** with a focus on applying **digital and cloud-based technologies** to transport, climate, and public-interest challenges in the UK.
