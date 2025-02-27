# Assessing Range Shifts of Coastal Species to Inform Conservation in California’s Biogeographic Transition Zones

## Overview
This project will inform a strategic conservation plan for monitoring and preserving biodiversity under climate change within the Dangermond Preserve. 
In collaboration with The Nature Conservancy, we will utilize statistical analysis to model current species distribution ranges and predict potential 
futures to be compiled in a public-facing web dashboard.

## Project Summary

Point Conception, located within the Dangermond Preserve, is one of California’s most prominent ecological transition zones, marking a major boundary between northern and southern marine ecoregions. Its unique position at the intersection of two major currents creates a steep gradient in oceanographic and ecological conditions, acting as a natural barrier to the range expansions of many marine species. Rocky intertidal species are vulnerable to climate change-induced habitat changes, including ocean acidification, rising sea levels, changes in water temperature, and more frequent and intense storms. Species ranges are expected to shift in response to a changing climate, but it is not known how biogeographic barriers such as Point Conception might affect or constrain such shifts. Currently, there is no comprehensive understanding of the ranges of intertidal species found in or near the Point Conception region. Using long-term ecological survey data from the MARINe network, this project will locate species range edges along the California coast and identify the species with range edges at or near Point Conception. Additionally, by incorporating current and projected environmental variables drawn from Bio-Oracle, the project will characterize potential species range shifts within the Point Conception region. In collaboration with The Nature Conservancy’s Dangermond Preserve, an interactive dashboard will be developed displaying current and potential future ranges of a variety of key intertidal species, which will be used both by conservation scientists and by donors and community members to understand the preserve's unique ecological significance. By improving data accessibility and visualization, the dashboard will support more effective conservation planning and environmental decision-making.


## Project Deliverables

We envision the below deliverables to be compiled into a web-based interactive map where users can explore the species distribution models,
with possible side-panels showing changes in abundance over time, and the report card value per species.

### Objective 1: 
#### Identify and map rocky shore species range edges along California’s coast.

A map portraying the California coastline broken into equal-size sections (i.e. 0.5-degree latitude or
100 km chunks), indicating the number of rocky intertidal species with northern/southern range
edges in each section of the coastline. A list of species which have range edges within the coastal
section encompassing Point Conception. These products are intended for conservation, grant
proposals/donors, and as an educational resource.

### Objective 2: 
#### Characterize potential species range shifts occurring within the Point Conception region.

A summary table for each species with range edges near Point Conception from Objective 1 listing
any significant changes in abundance over time within the Point Conception region. For those species
experiencing a range expansion near Point Conception, an indication of whether the shift is in the
arrival, increase, or persistence stage. This will be used by TNC to develop a coastal monitoring plan
and a preserve management access plan for the public.

### Objective 3: 
#### Predict species range shifts into the future.

Habitat suitability maps from species distribution models of each species with range edges near
Point Conception (from Objective 1), projected under future climate scenarios. This product is
intended to be used as an interactive tool and contribute to the future of the coastal monitoring plan.

### Objective 4: 
#### Create a range shift species list and a ranking system to prioritize monitoring for coastal range extensions/retractions within the Preserve.

A ‘report card’ for each of the species with range edges near Point Conception, representing the
degree of change compared to changes in abundance over time for the other sections of the coastline,
as well as the likelihood that they will shift past this transition zone from the species distribution
models. This product is also intended to be seen in conjunction with the interactive map to explore
potential species range extensions/contractions.

## Data Description

### Data files (acquired from data request from MARINe, early 2024):
- MARINe_longterm_data -> yearly photoplot data of targeted species assemblages
  - Phototranssummarysd_download.csv = summarized photo transect data, averaged across plots
  - Phototranraw_download.csv = raw photo transect data, percent cover per plot
- MARINe_biodiversity_data -> community-wide biodiversity data
  - cbs_data_CA_2023.xlsx = raw biodiversity data, includes its own metadata tab, point contact data for transects, quadrats and swaths
  - marine_species_taxonomy.csv = metadata on species taxonomy
