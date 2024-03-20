# Away-mini-project---Aston-2024

This repository contains the files necessary to recreate the CALANGO analyses for the mini-project undertaken at Aston Univeristy from Jan - Mar 2024.

Folders:
- feature2GO: contains 18 files (one for each species) with annotation term prevalence
- metadata: contains three metadata files - one with the ln-transformed maximum longevity values for all 18 primate species, and the other two with the residuals of a linear regression of maximum longevity and adult body mass for all 18 primate species, or for 17 primate species (excl. humans)
- parameters: contains five parameter files - one for the analysis with ln-transformed longevity values, two for the analyses with residuals (with and without humans), and two for the analyses with residuals (with and without humans) with no corrections for multiple hypothesis testing
- tree: contains two fully dichotomous, ultrametric phylogenetic trees (with and without humans)

RMarkdown files:
- AnAge data extraction and processing: this file contains the R code to extract and process the primate data from the AnAge database. This is used a
- CALANGO analyses: this file contains the R code used to run the five different CALANGO analyses
