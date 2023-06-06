# FP Empowerment Analyses using Urban Reproductive Health Initative data 
Contains code to replicate analyses for manuscript at this URL:



To entirely replicate the analyses from scratch, you must have separate established access to the URHI data through UNC. Request access to the data at https://data.cpc.unc.edu 

For a list of all packages required (and code to install them) for this analysis, see  `initialize_data_analyses.R`.

`combined_analysis/Combined_Analysis.R` recodes the data to standardize variables across contexts. You only need to do this once. The script saves the data in .Rds form to load for later sessions.

`combined_analysis/Replicate_PCA.R` replicates principal components analysis from Ewerling et al. 2017 on the longitudinal data and adds the principal components to the data as new variables

`combined_analysis/Empowerment_models_survey_domains.R` estimates mixed effects models on all items in the survey module 

`combined_analysis/Empowerment_models_PCA.R` estimates mixed effects models on principal components
