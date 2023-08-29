---
title: "readme"
author: "Pratyoosh Kashyap"
date: "`r Sys.Date()`"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```


## Exploring the Relationship among Stocks of Community Wealth, State Farm to School Policies, and the Intensity of Farm to School Activities
***
In this research we leverage the U.S. Department of Agriculture's 2019 Farm to School Census, a new disaggregated database of state-level Farm to School Policies, and a new county-level dataset of stocks of community wealth to answer three questions:
1. Is there a relation between community wealth and Farm to School adoption and intensity?
2. Given the stocks of community wealth, are state-level legislation supporting procurement and education activities in Farm to School related to program participation?
3. Are there spatial spillover effects among School Food Authorities in FTS programming?

## Code Files and Data
***
**This repository contains the following code files:**
1. Developing the Farm to School Intensity measures
2. Disaggregated measures of state Farm to School Policies
3. Combining the 2019 Farm to School Census data with the database of stocks of wealth, state Farm to School policies, and other control variables
4. Econometric analysis using the Heckman Selection Model
5. Creating maps for Farm to School Intensity and state Farm to School policies

**This repository contains the following data files:**
1. USDA FNS's 2019 Farm to School Census. Access here: https://farmtoschoolcensus.fns.usda.gov/census-results/about-data

2. Database on stocks of community wealth developed by Schmit et al. (2021) (https://doi.org/10.1016/j.foodpol.2021.102119). Access here: https://github.com/schmi-ny/County-Level-Community-Capital-Stocks/tree/main

3. Datasets of State Farm to School Policies, FIPS codes, RUUCs, and ZIP codes used for regression analysis.

