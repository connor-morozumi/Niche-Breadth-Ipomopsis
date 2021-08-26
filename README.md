This is the data and code repository for the published paper: Plant-Pollinator Interaction Niche Broadens in Response to Severe Drought Perturbations

Authors: Kelly L. Endres, Connor N. Morozumi, Xingwen Loy, Heather M. Briggs, Paul J. CaraDonna, Amy M. Iler, Devon A. Picklum, William A. Barr, Berry J. Brosi

Full citation:

DOI:

# Scope

How flexible are interaction niches under altered abiotic conditions? Here we investigate flower visitation niche breadth in a focal plant _Ipomopsis aggregata_.

This repository contains all code for Endres et al. 2021 manuscript investigating the effects of drought on Ipomopsis aggregata niche breadth. We utilized Ipomopsis visitation data from several sites over five years, 1997, 1998, 2001, 2012, and 2018, with 2012 and 2018 determined to be drought years. Between years we compared visitor abundance, community change, and richness. We also analyzed weather data to confirm drought year determination. 

# Data

This repository contains three datasets

* weather data from the Gothic field station: `gothicweather.csv`
* visit abundance by observation day: `visit.abundance.by.observation.day.csv` 
* total visits per site per year by each pollinator category: `total visits per site per year by each visitor catagory.csv`

# Code Overview

We've combined all analyses for the paper into one R Notebook titled `All_ipo.Rmd`. This consists of: 

1. Drought Analysis
+ Adonis
+ NMDS
2. Visitation Summary Statistics
3. Visitor Abundance
+ glmm abundance analysis
4. Richness
+ glmm analysis - Visit richness
+ iNEXT analysis - Visit richness
5. Community Change
+ Adonis analysis
+ NMDS
