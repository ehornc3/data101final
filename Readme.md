# Unraveling the Impacts of Climate Change

This repository contains the sources, datasets, and RMarkdown scripts used to produce the results in a study analyzing the relationship between climate change indicators and the prevelance of heat related illness in the United States.

## Reproducing this Study

To set up this project and reproduce the results in the study, follow these steps:

1. Clone this repository using a Git Client (May be CLI Git, Github Desktop, or RStudio's builtin Git integration).
2. Open `data101final.Rproj` file using RStudio.
3. Open `hri_analysis.Rmd` and knit the file.

## Data Sources

This section contains the data sources used in this study, as well as the corresponding files each of these datasets corresponds to.

### HRI Emergency Room Visits, Hospitilizations, Mortality per 100,000
<https://ephtracking.cdc.gov/apigateway/api/v1/getCoreHolder/439/1/all/all/1/2021,2020,2019,2018,2017,2016,2015,2014,2013,2012,2011,2010,2009,2008,2007,2006,2005,2004,2003,2002,2001,2000/0/0>
- hri_emergencyvisits.json
<https://ephtracking.cdc.gov/apigateway/api/v1/getCoreHolder/432/1/all/all/1/2021,2020,2019,2018,2017,2016,2015,2014,2013,2012,2011,2010,2009,2008,2007,2006,2005,2004,2003,2002,2001,2000/0/0>
- hri_hospitalization.json
<https://ephtracking.cdc.gov/apigateway/api/v1/getCoreHolder/370/1/all/all/1/2020,2019,2018,2017,2016,2015,2014,2013,2012,2011,2010,2009,2008,2007,2006,2005,2004,2003,2002,2001,2000/0/0>
- hri_mortality.json

### Atmospheric C02 Concentration
<https://climatedata.imf.org/datasets/9c3764c0efcc4c71934ab3988f219e0e/explore>
- Atmospheric_CO2_Concentration.csv

### Temperature Data by State
<https://www.kaggle.com/datasets/thedevastator/analyzing-u-s-warming-rates-insights-into-climat>
- climdiv_state_year.csv
- model_state.csv

## Authors

This repository is the work of data science students at Ramapo College for a final project.
- Ethan Horn
- David Lopez
- Alec Libroia