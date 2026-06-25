# air-pollution-mortality-analysis
This project analyzes California air pollution and mortality data using R. It involves data cleaning, merging monitor-level ozone and PM2.5 datasets, constructing a county-day panel, generating descriptive statistics and visualizations, and estimating fixed-effects regression models to examine the pollution–mortality relationship.
The repository contains my attempt to solve the coding assignment from PREDOC data tasks
(https://www.predoc.org/how-to-prepare)

Folder Description and Sources
Raw Data

The raw data were provided as part of the 2025 Predoc Data Task and contain daily air pollution measurements collected from monitoring stations across California counties.

data-task-2025-ozone.dta (.Rdata)
Contains county-monitor-day observations of ozone pollution, including ozone concentration measurements, Air Quality Index (AQI), pollution source indicators (AQS or AirNow), county identifiers, CBSA information, and mortality data.

data-task-2025-pm.dta (.Rdata)
Contains county-monitor-day observations of PM2.5 pollution measurements, including monitor identifiers, county identifiers, dates, and PM2.5 concentration levels.

Code
All code here is written and run in RStudio.
