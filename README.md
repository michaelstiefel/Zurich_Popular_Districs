# Popular districts in Zurich

This repository contains the code and data for medium blogpost about
popular areas in Zurich. It is part of the Udacity Nanodegree program.

## Motivation

Looking at moving decisions to infer popular areas can be interesting for newcomers who want
to find out which area is popular, or politicians who might need policies to
improve the quality in less popular areas.

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

Please see this Medium post for a detailed discussion: 
