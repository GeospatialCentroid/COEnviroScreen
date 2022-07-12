
# Colorado EnviroScreen

Colorado EnviroScreen is a data processing code base with a public-facing shiny application highlighting the spatial variability of specific Environmental Health and Environmental Justice challenges throughout Colorado. This document is intended to guide users in the generation of the Colorado EnviroScreen dataset that supports functions as the input to the shiny applications.

The Geospatial Centroid developed this content at Colorado State University under the direction and support of the Rojos Public Health Lab at CSU, the Institute for the Built Environment at CSU, and the Colorado Department of Public Health and Environment.

Questions and comments can be directed to Dan Carver at carverd@colostate.edu



## Vision

The code base for generating the Colorado EnviroScreen score dataset utilizes a hierarchical workflow that matches general scoring presented on the application
- EnviroScreen Score
  - Group Component Scores
    - Component Scores
      - individual Indicator Scores

This allowed for a module approach to the development. The primary motivator for this process was to allow for the quick regeneration of all elements if a single input feature was changed. This was accomplished by writing out intermediates at every step in the process. All data processing functions have a version and overwrite parameter to give the user the specificity needed to control how much data is regenerated or compiled from the existing intermediate file. In short, the code base will include what's already there unless told otherwise. This keeps it fast and flexible.

As with any codebase, this will require some maintenance and adjustment going forward. We hope that what is provided is a viable starting place for a long-lived and successful project.

## About this Training Material

This tutorial has 3 major sections
- [Setting up the local environment](https://geospatialcentroid.github.io/COEnviroScreen/dataProcessing/localEnv.html)
- [running the processing code](https://geospatialcentroid.github.io/COEnviroScreen/dataProcessing/processData.html)
- [details on specific functions](https://geospatialcentroid.github.io/COEnviroScreen/dataProcessing/individualFunctions.html)
