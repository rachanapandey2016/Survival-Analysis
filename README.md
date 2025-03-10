# Survival-Analysis with TCGA data   
**Project Description**  
---  
**Learning Objectives**  
---
**Research Questions**  
---  
Does high expression of TP53 influence prognosis on breast cancer patients?  

**Requirements**  
---
- R
- RStudio
- Rpackages:
  - TCGA
  - survminer
  - survival
  - tidyverse
  - SummarizedExperiment
- DESeq2

**Workflow**  
---
**0.Loading the required libraries**  
```
library(TCGAbiolinks)
library(survminer)
library(SummarizedExperiment)
library(tidyverse)
```
You can explore more on TCGAbiolinks pacakage from bioconductor through this link `https://rdrr.io/bioc/TCGAbiolinks/`  

***Getting clinical data for TCGA BRCA cohort**  
