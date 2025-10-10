<div align='center'>
    <a href='https://tula.org'><img height='75px' src=docs/logos/tula-logo.png /></a>
    &nbsp;&nbsp;&nbsp;&nbsp;
    <a href='https://hakai.org'><img height='75px' src=docs/logos/hakai-logo.png /></a>
</div>

# Time series of surface kelp canopy area derived from remotely piloted aerial systems (RPAS, or drone) surveys, Central Coast, British Columbia

https://doi.org/10.21966/9cbv-ra30

This data package represents a time series of canopy area of giant kelp, _Macrocystis pyrifera_, and bull kelp, _Nereocystis luetkeana_, derived from remotely piloted aerial system (RPAS or drones) surveys, along with relevant metadata. The kelp canopy is composed of the portions of fronds, stipes and blades floating on the surface of the water. RPAS surveys are conducted annually at long-term monitoring sites surveyed by the Hakai Institute on the Central Coast of British Columbia, Canada. These data are collected as part of the Hakai Institute Habitat Mapping Program whose broader goal is to document and understand long-term trends of kelp forests dynamics and drivers at local, regional and coast-wide scales. The Hakai Institute started using drones in 2015 as part of this work in order to capture site-level data on kelp forest distribution for long-term ecological research. 

This data package is freely available to everyone, following the principles of equitable access and benefit sharing. However, we expect all data users to give attribution to the data providers (read our data license) and the use of these data should happen in the light of fair use, i.e.: 1) respect the data providers, and provide helpful feedback on data quality, and 2) communicate and/or collaborate with the providers if you are considering using this dataset for manuscripts or other forms of reporting.

```
Reshitnyk, L., & Holmes, K. (2025). Time series of surface kelp canopy area derived from remotely piloted aerial systems (RPAS, or drone) surveys, Central Coast, British Columbia (v1.0). Hakai Institute. https://doi.org/10.21966/9cbv-ra30
```
## Method

Drone surveys are conducted annually in July/August during low tide (<1.5 m, chart datum) and collect RGB (red-green-blue) imagery. Canopy area is derived from drone-derived orthomosaics using a machine learning tool, the Kelp-O-Matic, which automates the detection of extent of kelp canopy area present in high-resolution orthomosaics. Areal data are classified to species level. Outputs are reviewed by a trained analyst. Canopy area (m2) data are provided as vector features (shapefiles) in NAD83 UTM Zone 9 clipped to each site area of interest (AOI) to ensure the same areas are compared over time and then published to a geodatabase. 

## Reports

The metadata report associated with this dataset can be found [here](https://github.com/HakaiInstitute/kelp-drone-mapping-data/blob/main/docs/Metadata_%20Time%20series%20annual%20kelp%20canopy%20area%20derived%20from%20drone%20surveys%2C%20Central%20Coast%2C%20British%20Columbia%20(ongoing).pdf)

## Resources

This data package includes a geodatabase which contains: 

- Polygon vector features of canopy kelp 
- Polygon vector features of the area of interest (AOI) of each monitoring site
- A metadata report (.pdf) which describes methods for imagery collection, generating orthomosaics and delineating kelp extent.
- Data dictionaries (.csv) which describe the attributes of the polygon vector features for canopy kelp. The data dictionaries are for the datasets included within CentralCoast_SeasonalDroneKelpPolygons.gdb.zip

## How to contribute

To contribute to the code or contents, please fork this repository, make your suggested modifications and generate a pull request (PR). For any issues related to the code or contents, please create an issue in this repository. A good issue sufficiently outlines the problem, and where possible suggests a solution. Please give the owners of this repository ample time to review issues or suggestions. Finally, for general inquires related to the data, please contact the data provider as listed in the referenced metadata record in the Hakai Catalogue. 

*This repository is generated via the [Hakai dataset repository template](https://github.com/HakaiInstitute/hakai-dataset-repository-template)*

