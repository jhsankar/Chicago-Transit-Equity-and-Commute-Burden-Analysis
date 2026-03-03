# Chicago-Transit-Equity-and-Commute-Burden-Analysis

## Overview
This GIS project examines how poverty, transit access, and commute burden intersect across Chicago neighborhoods using ArcGIS Pro and public spatial data.

## Sample Maps

### Poverty Choropleth Map

![Poverty Choropleth Map](MAPS/Choropleth-Poverty-Percentage-Map.jpg)

### Transit Density Map

![Transit Density Map](MAPS/Poverty-and-Transit-Access-Cluster.jpg)

### Cluster Analysis Map

![Cluster Analysis Map](MAPS/KDE-Transit-stops-Layout.jpg)

### Commute Burden Map

![Commute Burden Map](MAPS/Commute-Burden-Layout.jpg)

## Data Sources
- U.S. Census Bureau, American Community Survey (2022)
- CTA Bus Stops, City of Chicago Data Portal
- CTA Rail Stations, City of Chicago Data Portal
- Chicago Community Area Boundaries
- Census Block Groups / TIGER shapefiles

## Methods
This project used several GIS methods to analyze spatial patterns in transportation equity:

- Cleaned and joined ACS poverty and commute-time data to census block groups
- Created a **poverty choropleth map**
- Generated a **Kernel Density Estimation (KDE)** surface for CTA bus stops and rail stations
- Built a **bivariate spatial cluster analysis** combining poverty and transit density
- Calculated a **dominant commute-time category** for each block group
- Compared spatial patterns in transit supply with socioeconomic need

## Key Findings
- Poverty is concentrated heavily on Chicago’s South and West Sides.
- Transit density is strongest in and around downtown and the North Side.
- High-poverty neighborhoods often have only moderate transit access rather than the strongest access.
- Many of these same neighborhoods experience longer dominant commute times.
- The results suggest a mismatch between transit need and transit supply.
