This tutorial has 3 major sections
- [Setting up the local environment](https://geospatialcentroid.github.io/COEnviroScreen/dataProcessing/localEnv.html)
- [running the processing code](https://geospatialcentroid.github.io/COEnviroScreen/dataProcessing/processData.html)
- [details on specific functions](https://geospatialcentroid.github.io/COEnviroScreen/dataProcessing/individualFunctions.html)




## Setting up the local environment

The data processing code is stored in the Geospatial Centroid's GitHub, and needs to be downloaded or cloned to render in the local environment.
https://github.com/GeospatialCentroid/COEnviroScreen_dataProcessing

We've utilized a .rproj file to organize this work, and we recommend that you do the same.

With the repository on your local device, open the R Project file and then the `0_main.R` file. Barring special use cases, all data connected to the EnviroScreen score and shiny applications can be generated through edits within this script alone.

### Input datasets

The input data sets for the enviroscreen project are store in the Geospatial Centroid's GitHub. Please download this content. The following section will describe how to bring it into the R project while maintaining all relative links.

Current the following indicators are store as 7zip files within the folder. They will need to be extracted before they can be processed.

- "data/input/EJScreen/EJScreen.7z"
- "data/input/floodPlains/floodPlains.7z"
- "data/input/noise/CONUS_L50dBA_sumDay_exi.7z"
- "data/input/spatialLayers/justice40.7z"
