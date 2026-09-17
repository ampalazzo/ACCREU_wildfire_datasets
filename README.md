# ACCREU_wilfire_datasets
The dataset was produced by DTU in the context of the ACCREU project using the ForeFire wildfire spread modelling framework. Further information on the folder structure, file naming convention and data format is provided in the accompanying README.
# Burned Area Data from Fire Spread Simulation (ForeFire)

**Public Accelerator folder:** <links.html>

## Summary
This dataset contains burned area data from wildfire spread simulations conducted using the ForeFire model. The data cover three European regions (South, Central, and North) under multiple climate datasets and time periods: ERA5-Land reanalysis for 2008–2019, ClimEx2 historical simulations for 1991–2010, and ClimEx2 future projections under SSP2 for 2041–2060 and 2081–2100. The outputs are provided as ESRI Shapefiles containing simulated burned-area polygons, including the date of each fire event and total burned area in hectares. The effective spatial resolution is approximately 50 m, and all spatial data use the ETRS89 / LAEA Europe coordinate reference system (EPSG:3035). The dataset was produced by DTU in the context of the ACCREU project.

## Citation
<ADD PREFERRED CITATION / ZENODO DOI ONCE AVAILABLE>

> Soto Martin, Jorge; Meuriot, Ophélie; and  Drews, Martin. (2025). *Burned Area Data from Fire Spread Simulation (ForeFire)*. Zenodo. https://doi.org/<DOI>

## License
- **Data:**   This dataset is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) license.

## Repository Contents (Metadata only)
This GitHub repo hosts **only** the metadata (README and badges). Data files reside on Accelerator (see link above).

## Folder Structure (on Accelerator)
```text
/
├─ South/
│  ├─ era5-land_2008-2019/
│  ├─ historical_1991-2010/
│  ├─ ssp2_2041-2060/
│  └─ ssp2_2081-2100/
├─ Central/
│  ├─ era5-land_2008-2019/
│  ├─ historical_1991-2010/
│  ├─ ssp2_2041-2060/
│  └─ ssp2_2081-2100/
└─ North/
   ├─ era5-land_2008-2019/
   ├─ historical_1991-2010/
   ├─ ssp2_2041-2060/
   └─ ssp2_2081-2100/
```

Each dataset is stored as an ESRI Shapefile consisting of `.shp`, `.shx`, `.dbf`, and `.prj` files. Each shapefile contains burned-area polygons with the attributes `date` (date of the fire event) and `area_ha` (total burned area in hectares).

For questions or clarifications, please contact jsoma@dtu.dk or ophme@dtu.dk.

## Funding Acknowledgement

This work was supported by the **Assessing Climate Change Risk in Europe (ACCREU)** project, funded by the European Commission under the **Horizon Europe** programme.

**Project website:** [ACCREU Website](https://www.accreu.eu/)
