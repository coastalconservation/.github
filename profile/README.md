<h1 align="center">

coastalconservation 

</h1>

<h2 align="center">

Assessing Range Shifts of Coastal Species to Inform Conservation in California’s Biogeographic Transition Zones


## Table of Contents 
[Overview](#overview)

[Project Summary](#project-summary)

[Repository Structure](#repository-structure)

[Data Sources](#data-sources)

[Authors and Contributors](#authors-and-contributors) 




## Overview

This is a capstone project for the [Master of Environmental Data Science](https://bren.ucsb.edu/masters-programs/master-environmental-data-science) at [Bren School of Environmental Science and Management](https://bren.ucsb.edu/), University of California, Santa Barbara

More information relating to this project can be found on our [Bren project page](https://bren.ucsb.edu/projects/assessing-range-shifts-coastal-species-inform-conservation-californias-biogeographic)

## Project Summary

Point Conception, located within the Dangermond Preserve, is one of California’s most prominent ecological transition zones, marking a major boundary between northern and southern marine ecoregions. Its unique position at the intersection of two major currents creates a steep gradient in oceanographic and ecological conditions, acting as a natural barrier to the range expansions of many marine species. Rocky intertidal species are vulnerable to climate change-induced habitat changes, including ocean acidification, rising sea levels, changes in water temperature, and more frequent and intense storms. Species ranges are expected to shift in response to a changing climate, but it is not known how biogeographic barriers such as Point Conception might affect or constrain such shifts. Currently, there is no comprehensive understanding of the ranges of intertidal species found in or near the Point Conception region. Using long-term ecological survey data from the MARINe network, this project will locate species range edges along the California coast and identify the species with range edges at or near Point Conception. Additionally, by incorporating current and projected environmental variables drawn from Bio-Oracle, the project will characterize potential species range shifts within the Point Conception region. In collaboration with [The Nature Conservancy’s Dangermond Preserve](https://www.nature.org/en-us/about-us/where-we-work/united-states/california/stories-in-california/dangermond-preserve/?gclsrc=aw.ds&gad_source=1&gclid=CjwKCAiA2cu9BhBhEiwAft6IxId_BYjIHuN0FsWf_QelTl1TllgDfMKbc1aBCOvTv84xS9uQ-zx7PxoCboQQAvD_BwE), an interactive dashboard will be developed displaying current and potential future ranges of a variety of key intertidal species, which will be used both by conservation scientists and by donors and community members to understand the preserve's unique ecological significance. By improving data accessibility and visualization, the dashboard will support more effective conservation planning and environmental decision-making.

## Repository Structure

```
coastal_species_analysis 
|
├── data/                # Raw and processed data
│
├── scripts/             # Analysis and modeling scripts     
│	    │
│	    ├── range_classifcation/      # Scripts for species list & map creation 
│	    │
│	    ├── summary_table/           # Scripts for computing summary tables
│    	│
│    	├── modeling/             # Scripts for species distribution modeling
│	    │
│	    ├── R/     # Functions   
│
├── outputs/             # Results, figures, and reports
│
├── README.md      # Project overview & setup instructions
│   
└── .gitignore           

dangermond_dashboard
|
├── app/
│   ├── ui.R             # User interface components
│   ├── server.R         # Server-side logic
│   ├── global.R         # Loads shared functions & data
│   ├── www/             # Static assets (CSS, images, etc.)
│
├── data/                # Processed data pulled from analysis repo
│
├── R/             # Functions used in the dashboard
│               
├── README.md        # Overview & setup instructions
│
└── .gitignore 

```


## Data Sources 

### Data files (acquired from data request from MARINe, early 2024):
- MARINe_longterm_data -> yearly photoplot data of targeted species assemblages
  - Phototranssummarysd_download.csv = summarized photo transect data, averaged across plots
  - Phototranraw_download.csv = raw photo transect data, percent cover per plot
- MARINe_biodiversity_data -> community-wide biodiversity data
  - cbs_data_CA_2023.xlsx = raw biodiversity data, includes its own metadata tab, point contact data for transects, quadrats and swaths
  - marine_species_taxonomy.csv = metadata on species taxonomy
 

## Authors and Contributors 

#### Authors 

- Amanda Overbye  [GitHub](https://github.com/Aoverbye) | [Website]( ) | [LinkedIn]( ) 
- Ian Morris-Sibaja  [GitHub](https://github.com/imsibaja) | [Website](https://imsibaja.github.io/) | [LinkedIn](https://www.linkedin.com/in/imsibaja/) 
- Jordan Sibley  [GitHib](https://github.com/jordancsibley) | [Website](https://jordancsibley.github.io/) | [LinkedIn](https://www.linkedin.com/in/jordancsibley/)  
- Matteo Torres  [GitHub](https://github.com/matteo-torres) | [Website](https://matteo-torres.github.io/) | [LinkedIn](www.linkedin.com/in/matteo-torres-876a62234)

#### Client 

Dr. Erica Nielsen  | Anthony W. LaFetra Point Conception Research Fellow | The Nature Conservancy in California | erica.nielsen@tnc.org

#### Advisor 

Dr. Bruce Kendall | Bren School Professor; Associate Dean | [Bren page](https://bren.ucsb.edu/people/bruce-kendall)
