# Moira Flood Analysis Project

This repository contains the notebook **A4-Final-MoiraFloodAnalysis.ipynb**, which performs a spatial analysis of flood events and dam locations in the Moira LGA (Local Government Area), Victoria, Australia.\

# **GEOM90006: Spatial Data Analytics – Assignment 4**
##### **Group: G49**
##### Takamasa Oshiro: 1626510, Shriya Krishna Kumar: 1418627, Ankita Holey: 1621609
##### Lecturer: A/Prof. Jagannath Aryal

## Dataset Definitions

| Variable             | File Path                                              | Description                                                                              |
| -------------------- | ------------------------------------------------------ | ---------------------------------------------------------------------------------------- |
| `vic_shp`            | `data/vic-data/victoria_state.shp`                     | Shapefile of the state boundary of Victoria, Australia (GDA94).                          |
| `moira_shp`          | `data/Moira_LGA.shp`                                   | Shapefile of the Moira LGA boundary .                                        |
| `vic_rainfall`       | `data/rainfall.2022-2025_vic.csv`                      | CSV of rainfall measurements across Victoria from 2022 to 2025.                          |
| `flood_extent_moira` | `data/1-in-100_flood_extent_Moira_projectedxy.geojson` | GeoJSON layer showing the 1-in-100 year flood extent in Moira . |
| `moira_dem`          | `data/Moira_using_coords.tif`                          | Digital Elevation Model (DEM) raster for Moira region.                                   |
| `dam`                | `data/moira_dam_basin.geojson`                         | GeoJSON of dam and retarding basin locations in Moira LGA .                  |

## Repository Structure

```
├── data/
│   ├── vic-data/
│   │   └── victoria_state.shp
│   ├── Moira_LGA.shp
│   ├── rainfall.2022-2025_vic.csv
│   ├── 1-in-100_flood_extent_Moira_projectedxy.geojson
│   ├── Moira_using_coords.tif
│   └── moira_dam_basin.geojson
├── A4-Final-MoiraFloodAnalysis.ipynb
└── README.md
```

## Dependencies

Make sure to use spanalytics python env.

## Running the Notebook

Having the folder as is, the code can be run using spanalytics python env.

## Outputs

- All results are present inline with interpretation in markdown 


