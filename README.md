# Proximity and Knowledge Spillovers
## Measuring the University-Industry Link via Co-Authorship Analysis
This repository contains the data and analysis on knowledge spillovers and proximity in the HealthTech sector. The study uses Scopus bibliometric data to identify and quantify university–industry (U–I) collaborations through co-authorship analysis.

## Research Overview
**Objective:** Identify and quantify university–industry collaborations in HealthTech using Scopus publication data.
**Methodology:** Co-authorship analysis — filtering for papers jointly authored by at least one university and one private company.
**Core Hypothesis:** A strong **home bias** exists, meaning firms prefer to collaborate with universities in their own country (or region). This supports the theory that face-to-face interaction is crucial for transferring complex tacit knowledge.

## Notebook Outline
The notebook `proximity_knowledge_spillovers.ipynb` covers the following analyses:
1.**Data Loading & Cleaning** — Importing and validating the Scopus dataset
2.**Institution Classification** — Tagging each affiliation as university, company, hospital, or other
3.**Country Extraction** — Parsing country information from affiliation strings
4.**Home-Bias Analysis** — Testing whether U–I co-authored papers tend to involve same-country collaborators
5.**Top Collaborating Institution Pairs** — Most frequent (university, company) pairings
6.**Top Collaborating Countries** — Country-level overview of U–I publication activity
7.**Cross-Country Collaboration Matrix** — Heatmap of international knowledge corridors
8.**Collaboration Network Visualisation** — Graph of country-level U–I ties (NetworkX)
9.**Temporal Evolution** — Trends in U–I collaboration share over time
10.**Choropleth Maps** — Geographic distribution of HealthTech and U–I papers (GeoPandas)
11.**Spatial Autocorrelation** — Global Moran's I and LISA cluster maps
12.**Proximity Effect on Citation Impact** — Mann-Whitney test comparing home-bias vs. cross-country papers by citation count

:


