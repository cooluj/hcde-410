#HCDE410
Files for HCDE410 - Assignment A1

Adapted from # cdsw-2020 https://wiki.communitydata.science/Seattle_open_data


# A1 — Working with Open Data

**Dataset:** Burke-Gilman Trail Counter North of NE 70th St

**Source:** https://data.seattle.gov/d/2z5v-ecg8

**Data period:** January 1 – December 31, 2019

**Date accessed:** October 12th 2026

**License / Terms of Use:** The dataset is provided by the City of Seattle and designated as Public Domain. The accompanying LICENSE file contains the MIT license for the course materials.

## Project Overview

This project analyzes bicycle and pedestrian traffic along Seattle's Burke-Gilman Trail using hourly counter data from 2019. The goal is to identify patterns in trail usage and explore how they relate to commuting, recreation, time of day, and direction of travel.

## Questions I Asked

1. When is the trail busiest and quietest?
2. Do cyclists and pedestrians use the trail at different times?
3. Is there evidence of commuting patterns compared to recreational usage?
4. How does the direction of travel change between morning and evening?

## How to Re-run

1. Open `A1.ipynb` in Jupyter Notebook or JupyterHub.
2. Ensure Python is installed with `requests`, `pandas`, and `matplotlib`.
3. Run all notebook cells in order.
4. The notebook retrieves data from Seattle's open-data API, processes the hourly traffic counts, and generates visualizations for analysis.

## Data Limitations

The dataset represents traffic recorded at a single counter location and does not measure people's reasons for using the trail. Findings should therefore be interpreted as patterns of traffic behavior rather than definitive evidence of commuting or recreation.