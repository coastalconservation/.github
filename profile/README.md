<h2 align="center"> 
  
<img src="https://github.com/coastalconservation/.github/blob/main/photos/cc-hexlogo-lowquality.png?raw=true" alt="Coastal Conservation Capstone group logo: hex sticker with rocky coastline and lighthouse illustration" width="300">

<h1 align="center">

Assessing Range Shifts of Coastal Species to Inform Conservation in California’s Biogeographic Transition Zones

## Table of Contents 
[Overview](#overview)

[Project Summary](#project-summary)

[Objectives](#objectives)

[Data Sources](#data-sources)

[Authors and Contributors](#authors-and-contributors) 


## Overview

This is a capstone project for the [Master of Environmental Data Science](https://bren.ucsb.edu/masters-programs/master-environmental-data-science) at [Bren School of Environmental Science and Management](https://bren.ucsb.edu/), University of California, Santa Barbara

More information relating to this project can be found on our [Bren project page](https://bren.ucsb.edu/projects/assessing-range-shifts-coastal-species-inform-conservation-californias-biogeographic)

## Project Summary

Point Conception, located within the Dangermond Preserve, is one of California’s most prominent ecological transition zones, marking a major boundary between northern and southern marine ecoregions. Its unique position at the intersection of two major currents creates a steep gradient in oceanographic and ecological conditions, acting as a natural barrier to the range expansions of many marine species. Rocky intertidal species are vulnerable to climate change-induced habitat changes, including ocean acidification, rising sea levels, changes in water temperature, and more frequent and intense storms. Species ranges are expected to shift in response to a changing climate, but it is not known how biogeographic barriers such as Point Conception might affect or constrain such shifts. Currently, there is no comprehensive understanding of the ranges of intertidal species found in or near the Point Conception region. Using long-term ecological survey data from the MARINe network, this project will locate species range edges along the California coast and identify the species with range edges at or near Point Conception. Additionally, by incorporating current and projected environmental variables drawn from Bio-Oracle, the project will characterize potential species range shifts within the Point Conception region. In collaboration with [The Nature Conservancy’s Dangermond Preserve](https://www.nature.org/en-us/about-us/where-we-work/united-states/california/stories-in-california/dangermond-preserve/?gclsrc=aw.ds&gad_source=1&gclid=CjwKCAiA2cu9BhBhEiwAft6IxId_BYjIHuN0FsWf_QelTl1TllgDfMKbc1aBCOvTv84xS9uQ-zx7PxoCboQQAvD_BwE), an interactive dashboard will be developed displaying current and potential future ranges of a variety of key intertidal species, which will be used both by conservation scientists and by donors and community members to understand the preserve's unique ecological significance. By improving data accessibility and visualization, the dashboard will support more effective conservation planning and environmental decision-making.

<h4 align="center">
<img src="https://github.com/coastalconservation/.github/blob/main/photos/RANGESHIFT.png" alt="Intertidal species range shift diagram" width="650">

Intertidal species range shift

## Objectives 

This project supports The Nature Conservancy’s Dangermond Preserve by identifying the historical and current ranges of intertidal species in the area and assessing their vulnerability to climate change-induced habitat shifts or loss. To achieve this goal, our team will:

- Identify and map the range edges of rocky shore species along California’s coast.
- Characterize and predict potential range shifts occurring within the Point Conception region.
- Establish a ranking system to prioritize species for monitoring based on the likelihood of coastal range extensions or retractions within the Preserve.

The code used to conduct these analyses can be found in the [coastal-species-analysis](https://github.com/coastalconservation/coastal_species_analysis) repository. All components of the project are compiled into an interactive dashboard, built using R Shiny, available in the [dashboard](https://github.com/coastalconservation/dashboard) repository.


## Data Sources 

Read more about our data in the [*Data Sources*](https://github.com/coastalconservation/coastal_species_analysis?tab=readme-ov-file#data-sources) section of our `coastal-species-analysis` repository. 

| Data                                                                                         | Source 
| -------------------------------------------------------------------------------------------- | ------------------------------------- |
| **Coastal Biodiversity Survey Data**: community-wide biodiversity data of intertidal species |  Acquired from data request from MARINe, early 2024) |
| **Bio-ORACLE Environmental variable rasters**: Environmental inputs for species distribution models  |  Through the `{biooracler}` R package via ERDDAP server |
| **California Boundary**: Shapefile used for mapping | US Census Bureau TIGER/Line Shapefiles | 
| **Dangermond Preserve Simple Boundary**: Shapefile used for mapping | Dangermond Preserve Geospatial Hub | 
| **Coastline Segements**: Line segement of california coastline  | Created by Dr. Erica Nielsen using ArcGIS | 


## Authors and Contributors 

#### Authors 

- Amanda Overbye  [GitHub](https://github.com/Aoverbye) | [Website](https://aoverbye.github.io/) | [LinkedIn](https://www.linkedin.com/in/amanda-overbye-3a6364161/) 
- Ian Morris-Sibaja  [GitHub](https://github.com/imsibaja) | [Website](https://imsibaja.github.io/) | [LinkedIn](https://www.linkedin.com/in/imsibaja/) 
- Jordan Sibley  [GitHib](https://github.com/jordancsibley) | [Website](https://jordancsibley.github.io/) | [LinkedIn](https://www.linkedin.com/in/jordancsibley/)  
- Matteo Torres  [GitHub](https://github.com/matteo-torres) | [Website](https://matteo-torres.github.io/) | [LinkedIn](https://www.linkedin.com/in/matteo-torres-876a62234/)

#### Client 

Dr. Erica Nielsen  | Anthony W. LaFetra Point Conception Research Fellow | The Nature Conservancy in California | erica.nielsen@tnc.org

#### Advisor 

Dr. Bruce Kendall | Bren School Professor; Associate Dean | [Bren page](https://bren.ucsb.edu/people/bruce-kendall)
