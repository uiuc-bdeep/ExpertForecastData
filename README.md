# ExpertForecastData
These data are collected as part of Christensen P., Gillingham K., and Nordhaus, W. 2018. Uncertainty in forecasts of long-run economic growth

This file describes the data and programs used to replicate results reported in: "Uncertainty in Forecasts of Long-Run Economic Growth."  
Please contact pchrist@illinois.edu with any questions.
NOTE: Pathnames must be changed in all files.

********************************************Expert Survey Forecasts

(1) Responses and Quantile Estimates from Expert Survey: ExpertForecastData

Notes: 
- Expert names are anonymized.  Expert vector refers to individuals.
- Period codes indicate 40-year or 90-year forecast horizon.

(2) To recover the mean and sigma of expert forecast distributions (reported in Table 1): run matlab script: FindNormalParameters.

Notes: 
 - This program computes the mean and sigma for expert forecasts by region and horizon. 
 - Pathnames must be changed.  Mean [column 10] and Sigma [column 11] contained in output file (estimatedparameters).

