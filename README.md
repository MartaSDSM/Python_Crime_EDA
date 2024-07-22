
# Python Project - Crime data Exploratory Data Analysis

This Python project focuses on conducting an Exploratory Data Analysis (EDA) of crime data from various regions in the UK, tailored for a real estate company, specifically targeting the Head of Sales, Nadine Green. The objective is to provide insights into crime trends to assist Nadine in making informed decisions regarding property sales. The project requires analyzing crime data from at least three police forces spanning a minimum of two years, merging it with third-party datasets, and conducting detailed EDA. The deliverables include a Project Statement of Work, a Trello board for task management, Jupyter Notebooks for preprocessing and analysis, an analysis report, and a stakeholder management presentation. Effective stakeholder management and a conservative approach to project scope are emphasized, with a focus on delivering actionable insights to meet Nadine's needs and expectations.

## Installation

Install my-project with npm

```bash
  pip install pandas
  pip install numpy
  pip install matplotlib
  pip install seaborn
  pip install folium
  pip install geopandas
```
    import pandas as pd
    import numpy as np
    import matplotlib.pyplot as plt
    import seaborn as sns
    import folium
    from folium.plugins import MarkerCluster
    import geopandas as gpd
## Documentation

[Documentation](https://linktodocumentation)

Data on average house prices since january 1995 to december 2023 by property type (do pre-processing for this as well)
REferences: https://www.gov.uk/government/statistical-data-sets/uk-house-price-index-data-downloads-december-2023. This would be used to further analyse housing prices.

Submission folder
PoliceForceData - Folder with all monthly data from march 2022 to march 2024 for the 3 police forces in Bristol, cambridge and oxford.
ExploratoryDataAnalysis -  Jupyter notebook with the analysis
LSOA_2001_EW_BFC_V2.cpg, LSOA_2001_EW_BFC_V2.dbf, LSOA_2001_EW_BFC_V2.prj, LSOA_2001_EW_BFC_V2.shp, LSOA_2001_EW_BFC_V2.shx - Shape me files used for mapping the cities
LSOA_codesAndNames.csv - reference for LSOA codes and corresponding LSOA names
NormalisedPopulaiton2021-2022.xlsl - Population density data per LSOA codes
PreProcessing - Jupyter notebook with the preprocessing data