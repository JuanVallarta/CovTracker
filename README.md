# CovTracker

This interactive shiny/flexdashboard (R/FINDCovTracker) tool allows you to observe the daily number of Covid-19 tests, cases and deaths, and the corresponding average rates per capita (1000 people), reported by each country on a monthly and quarterly basis. 
The tool reads the data folder of this repository which is copied and updated from https://github.com/finddx/FINDCov19TrackerData on a daily basis via github actions (.github/workflows folder). The online version of this tool can be found in https://juanvallarta.shinyapps.io/FINDCovTracker/

EXTENDED version: In the R folder there is an extended version of the dashboard (FINDCovTrackerEXTENDED.Rmd) with additional features from the requested in the project. This features include time lines charts, maps, and the option to filter by date ranges. An online version of this extended version can be found in https://juanvallarta.shinyapps.io/FINDCovTracker_EXTENDED/
