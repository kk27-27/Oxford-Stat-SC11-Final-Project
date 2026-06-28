# Oxford-Stat-SC11-Final-Project

This project investigates whether El Niño–Southern Oscillation (ENSO) indicators 
(specifically the Oceanic Niño Index, ONI) provide useful predictive information 
for California winter precipitation. We find that ENSO has a weak positive 
association with California winter precipitation, the predictive power of ONI is
statistically weak across models, including ENSO provides only marginal 
improvements in forecasting performance, and ENSO does not significantly improve
the prediction of extreme wet winters. 

## Data Sources

- NOAA Oceanic Niño Index (ONI): https://www.cpc.ncep.noaa.gov/data/indices/oni.ascii.txt  
- NOAA Climate at a Glance (California Precipitation): https://www.ncei.noaa.gov/access/monitoring/climate-at-a-glance/

## Final Recommendation

Overall, ENSO indicators alone do not substantially improve predictive skill for
California winter precipitation, though they may still provide limited 
supplementary information in broader forecasting systems; "No, No, El Niño
forecasts do not appear to improve predictions substantially." 

## Reproducibility

To reproduce the analysis:
1. Open the R project file (.Rproj)
2. Ensure that the necessary packages are installed:
     - tidyverse
     - dplyr
     - ggplot2
     - gridExtra
     - forecast
     - tseries
     - ggrepel
     - KFAS
     - extRemes
3. Ensure `data.csv` is in the project directory (California water precipitation data)
4. Knit `Oxford Stat SC11 Final Project.Rmd`
