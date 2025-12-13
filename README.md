# Biodiversity-Intactness-Index-change-in-Phoenix-AZ

You can access the full analysis of the project in this [Github repository](https://github.com/Awoo56709/Biodiversity-Intactness-Index-change-in-Phoenix-AZ)

## About
### Purpose
This notebook investigates changes in the Biodiversity Intactness Index (BII) in the Phoenix subdivision between 2017 and 2020. The goal is to understand how rapid urban expansion has affected biodiversity.

### Highlights
- Imported and explored BII raster datasets (2017, 2020) from the Microsoft Planetary Computer.  
- Clipped rasters to the Phoenix subdivision shapefile.  
- Calculated the percentage of area with BII ≥ 0.75 for both years.  
- Visualized areas of biodiversity loss between 2017 and 2020.  

### About the Data
- **BII Time Series (2017, 2020):** Global 100m projections of biodiversity intactness, accessed via Microsoft Planetary Computer STAC catalog.  
- **Phoenix Subdivision Shapefile:** Census County Subdivision shapefiles for Arizona, used to define the study area.  
- **Contextual Data:** Optional basemap tiles from `contextily` for geographic context.  

### Data Access

All datasets used in this analysis are publicly available. Due to their size, large spatial files are not stored in the repository and must be obtained separately.

Vector Data (manual download)
    - U.S. Census Bureau – TIGER/Line Arizona County Subdivision Shapefiles

    -  Arizona county subdivision shapefile is required to extract the Phoenix subdivision boundary.

    - Because of its file size, this dataset is excluded from version control and listed in .gitignore.

    - Users must download the shapefile manually from the U.S. Census Bureau: TIGER/Line Shapefiles

    - After downloading, place the extracted files in: data/tl_2024_04_cousub/

Raster Data (remote access)
Biodiversity Intactness Index (BII)

    - BII rasters are accessed directly from the Microsoft Planetary Computer.

    - Data are retrieved using the Planetary Computer STAC API within the Jupyter notebook.

    - Queried: 2017 and 2020.

    - Raster files are not stored locally; they are streamed during analysis.

    - No API key is required — authentication is handled with the planetary_computer.sign() function.

Note: An active internet connection and the appropriate Python packages are required to reproduce this workflow.

### References
- Levitt, Z., & Eng, J. (2021). *Where America’s developed areas are growing: ‘Way off into the horizon’.* The Washington Post. https://www.washingtonpost.com/nation/interactive/2021/land-development-urban-growth-maps/  

- Gassert, F., Mazzarello, J., & Hyde, S. (2022). *Global 100m Projections of Biodiversity Intactness for the years 2017-2020 [Technical Whitepaper].* https://ai4edatasetspublicassets.blob.core.windows.net/assets/pdfs/io-biodiversity/Biodiversity_Intactness_whitepaper.pdf  

- Microsoft Planetary Computer, STAC Catalog. Biodiversity Intactness ('io-biodiversity'). [Dataset]. https://planetarycomputer.microsoft.com/dataset/io-biodiversity Accessed 6 December 2023.

- Galaz García, C. (2025). Final project. EDS 220: Working with Environmental Datasets. https://meds-eds-220.github.io/MEDS-eds-220-course/assignments/final-project.html

