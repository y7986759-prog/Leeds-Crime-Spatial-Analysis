# Spatial Analysis of Crime in Leeds (June–November 2025)

## Project Background
This project investigates the spatial distribution of recorded street-level crime in Leeds using open data from the UK Police API and official boundary datasets. The aim is to explore spatial patterns of crime and provide insights that could support public understanding and local decision-making.

## Data Sources
- UK Police API: Street-level crime data by month.
- Office for National Statistics (ONS): Leeds LSOA and LAD boundary shapefiles.

## Methods
The workflow includes:
1. Collecting monthly crime data using the UK Police API.
2. Pre-processing and cleaning spatial data.
3. Spatially joining crime points to LSOA boundaries.
4. Aggregating crime counts and calculating crime density.
5. Visualising spatial patterns using maps.

## How to Run
1. Open the Jupyter notebook `analysis.ipynb`.
2. Ensure all required data files are stored in the `data/` folder.
3. Run all cells from top to bottom.

## Output
The notebook produces spatial visualisations of crime distribution and density across Leeds LSOAs.

## Author
Student ID: 201995399
