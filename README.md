This repository contains all the scripts and data needed to reproduce the analyses presented in the published manuscript. 

To replicate the analyses, use RStudio to run the `parkrun_survey_analysis.R` script from the `analysis_code` directory.

The `analysis_code` directory should be in the same directory as the `data` directory and an empty version of the `outputs` directory (the `outputs` directory currently contains the outputs generated by the `parkrun_survey_analysis.R` script - running the `parkrun_survey_analysis.R` script will reproduce these outputs). 

When run in RStudio, the `parkrun_survey_analysis.R` script will read the survey data in the `data` directory, and output analysis results (including assumption checks) to the `outputs` directory. 
