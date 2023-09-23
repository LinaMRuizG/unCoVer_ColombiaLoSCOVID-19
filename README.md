# Survival analysis of  bed pathways and hospital Length of Stay (LoS):  A non-concurrent cohort study of Colombia COVID-19 patients. An unCoVer network project
In this project is estimated the Length of Stay in hospital bed types (i.e., Hospital and ICU) of Colombia COVID-19 patients. This is a survival analysis using Accelerated Failure Time (AFT) models. See https://journals.plos.org/plosone/article/metrics?id=10.1371/journal.pone.0278429

## Description of files in this repository

- `dataBases/` contains some of the databases used in the analysis. However, some databases are not uploaded because their size. Please contact me if you require them. The databases used here are from https://github.com/LinaMRuizG/unCoVer_processingData
- `figures/` contains some of the figures product of some analysis
- `scriptsR/` contains the main analysis which are the AFT models for the LoS and the LoS adjusted for covariables (i.e., Bed Pathway, Outcome, Age, Sex, epidemic waves, epidemic peaks and valleys, and vaccination period). Please refer to the main text. These codes are written in R-project.
- `scriptsW/` contains additional analysis such as the methodology developed to estimate the epidemic waves and peaks-valleys. These codes are written in Mathematica software.
