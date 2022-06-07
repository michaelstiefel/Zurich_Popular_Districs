# Popular districts in Zurich

This repository contains the code and data for medium blogpost about
popular areas in Zurich. It is part of the Udacity Nanodegree program.

## Libraries used

numpy: 1.21.6
pandas: 1.3.5
matplotlib: 3.5.1
seaborn: 0.11.2
geopandas: 0.10.2
imageio: 2.19.2

## Motivation

Looking at moving decisions to infer popular areas can be interesting for newcomers who want
to find out which area is popular, or politicians who might need policies to
improve the quality in less popular areas.

This analysis will answer three questions:

1) Which districts (German: Kreise) do residents of Zurich preferably move to and which districs are unpopular so that residents leave them?
2) Which districts are most popular for newcomers moving to Zurich from outside?
3) Which district sees the most new building projects for apartments?

## Files in the repository

- Zurich-Popular-Districts.ipynb : Jupyter notebook that contains the full analysis
- ./data/rawdata/Buildings_Zuerich.csv : Backup data for the number of new flats in each year
- ./data/rawdata/Umzuege_Zuerich.csv : Backup data for the moving of residents in Zurich between districts
- ./data/rawdata/Newcomers_Zuerich.csv : Backup data for the moving decisions of Newcomers
- ./data/geodata/geodata_kreise: folder to access the shapefiles for the city of Zurich with districts embedded
- ./data/geodata/geodata_quartiere: folder to access the shapefiles for the city of Zurich with quarters embedded (not used here because difficult to merge with the other data)
- ./results/gif_newcomers_across_years.gif
- ./results/gif_netchanges_across_years.gif
- ./results/NewFlatsAcrossDistricts.png
- ./results/NewBuildingsAcrossDistricts.png
- ./results/Zurich_Districts.png

## Data set

All the data for this project stems from the open administrative data provided
by the city of Zurich. Those are

- moving statistics for residents in Zurich (when residents move from one district to another) https://data.stadt-zuerich.ch/dataset/bev_umzuege_jahr_quartier_od3555
- moving statistics for newcomers in Zurich https://data.stadt-zuerich.ch/dataset/bev_zuz_jahr_quartier_od3511
- data on building activities https://data.stadt-zuerich.ch/dataset/bau_neubau_whg_bausm_rinh_geb_projstatus_quartier_seit2009_od5011

In the Jupyter Notebook, direct links to those datasets will be used, however, the current
data set is also available as .csv in the data/rawdata folder of this repository
for later replication.

In the data folder, there is also a folder geodata_kreise which contains the shapefiles
used in this project and the blogpost for visualizing the results in maps.

## How to use this repository

The virtual environment blogpost-venv contains all packages needed for this project,
including geopandas for working with shapefiles and imageio for creating GIFs.

The Jupyter notebook contains all the code used for this analysis and direct links to the data.

## Results

Please see this Medium post for a detailed discussion: https://medium.com/@ultimate_icterine_crab_125/zurichs-most-popular-districts-ed391b40c8c8

## Acknowledgements

This blogpost used the open, administrative data by the city of Zurich. The data is available here: https://data.stadt-zuerich.ch/
