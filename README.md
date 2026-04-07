# Proximity and Knowledge Spillovers
## Measuring the University-Industry Link via Co-Authorship Analysis
This repository contains the data and analysis on knowledge spillovers and proximity in the HealthTech sector. The study uses Scopus bibliometric data to identify and quantify university–industry (U–I) collaborations through co-authorship analysis.

## Research Overview
- **Objective:** Identify and quantify university–industry collaborations in HealthTech using Scopus publication data.

- **Methodology:** Co-authorship analysis — filtering for papers jointly authored by at least one university and one private company.

- **Core Hypothesis:** A strong **home bias** exists, meaning firms prefer to collaborate with universities in their own country (or region). This supports the theory that face-to-face interaction is crucial for transferring complex tacit knowledge.

## Key Findings
- **Home Bias Support:** The analysis confirms the hypothesis, showing that 84.4% of U-I collaborations occur between institutions in the same country.

- **Institutional Classification:** The algorithm successfully classified 987 papers, identifying that 67.9% of the dataset involves direct University–Industry co-authorship.

- **Knowledge Hubs:** The United States, China, and Italy emerge as top countries for U-I paper volume in this dataset.

## Notebook Outline
The notebook `proximity_knowledge_spillovers.ipynb` covers the following analyses:

**Data Loading & Cleaning:** Importing and validating Scopus datasets.

**Institution Classification:** Using keyword-based parsing to tag affiliations as univ, company, hospital, or research_inst.

**Country Extraction:** Parsing geographic information from affiliation strings.

**Home-Bias Analysis:** Testing if U–I co-authored papers involve same-country collaborators.

**Network Visualization:** Graphing country-level U–I ties using NetworkX.

**Spatial Autocorrelation:** Calculating Global Moran's I and LISA cluster maps to identify geographic clustering of innovation.

**Impact Analysis:** Comparing citation counts between "home-bias" and cross-country collaborations.

## Requirements
The analysis is built with Python 3 and requires the following libraries:
- **Data Analysis:** `pandas`, `numpy`
- **Visualization:** `matplotlib`, `seaborn`
- **Geospatial Analysis:** `geopandas`, `libpysal`, `esda`, `splot`
- **Network Science:** `networkx
To install the dependencies, you can run:
`pip install pandas numpy matplotlib seaborn geopandas libpysal esda splot networkx`

## Data Source
The analysis uses a Scopus dataset covering the years 2020-2024




