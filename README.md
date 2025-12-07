# Biodiversity-Intactness-Index-change-in-Phoenix-AZ

You can access the full analysis of the project in this [Github repository]([https://github.com/Awoo56709/Biodiversity-Intactness-Index-change-in-Phoenix-AZ](https://github.com/Awoo56709/Biodiversity-Intactness-Index-change-in-Phoenix-AZ/tree/main))

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



### References
- Levitt, Z., & Eng, J. (2021). *Where America’s developed areas are growing: ‘Way off into the horizon’.* The Washington Post. https://www.washingtonpost.com/nation/interactive/2021/land-development-urban-growth-maps/  
- Gassert, F., Mazzarello, J., & Hyde, S. (2022). *Global 100m Projections of Biodiversity Intactness for the years 2017-2020 [Technical Whitepaper].* https://ai4edatasetspublicassets.blob.core.windows.net/assets/pdfs/io-biodiversity/Biodiversity_Intactness_whitepaper.pdf  
- Microsoft Planetary Computer, STAC Catalog. Biodiversity Intactness ('io-biodiversity'). [Dataset]. https://planetarycomputer.microsoft.com/dataset/io-biodiversity Accessed 6 December 2023.
