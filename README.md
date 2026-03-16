# Music2Brain
The data and code that can be used to reproduce the results described in the paper "Measuring the Effects of Unexpected Deviations Of Musical Patterns on Predictive Brain Functions"

# Navigating source tree

`brainwaves_anova_with_2var.ipynb` : This is the Jupytr notebook that defines several utility functions to process raw data from MindMonitor device.

`MindMonitorData` : This is the sub-folder with all the anonymized raw data captured from MindMonitor device for each of the six participants. Under this folder, files are organized as Participant<#> {Harmony|Melody|Rhythm}.csv for each participant. 

`MindMonitorData/MindMonitorAnovaData-Anonymized.xlsx` collects all the data generated from running `brainwaves_anova_with_2var.ipynb` and creates the statistical summary and charts. 


