# ENVS 193DS, Homework 3

Spring 2025

## General information

The dataset *ENVS-193DS_caffeine_hw_2.csv* was tracked on Google Sheets by Kai Suzuki. 

The referenced paper is from Parejo, S. G., Piacenza, S. E., García, R., Ordóñez, C., and Valverde, R. A. 2025. Nesting population trend of the leatherback sea turtle in Bocas del Toro province and Comarca Ngäbe-Buglé, Panama for the period 2002–2022. Global Ecology and Conservation 57:e03415. [10.1016/j.gecco.2025.e03415](https://doi.org/10.1016/j.gecco.2025.e03415)

This repository is for a homework assignment in Spring 2025 for ENV S193DS, taught by An Bui at the University of California, Santa Barbara. The directions followed can be found [here](https://spring-2025.envs-193ds.com/assignments/homework-03)

### Packages

```
library(tidyverse) # general data tasks
library(here) # managing files
library(gt) # for table construction
library(janitor) # for data cleaning
library(readxl) # bringing excel files into R
library(dplyr) # for data cleaning
mydata <- read_csv("../data/ENVS-193DS_caffeine_hw2.csv") # personal data 
```

## Data and file information

File structure:

```
.
├── ENVS-193DS_homework-03.Rproj
├── README.md
├── code                                     # code folder
│   ├── homework.qmd                         # keys
│   └── homework.html                        # rendered output from .qmd
├── data                                     # data folder
│   └── ENVS-193DS_caffeine_hw2.csv          # personal data
└── images
    ├── sketchHW3.jpg                        # image of sketch
    └── draftHW3.jpg                         # image of draft
```

All code is in the `code` folder. The code analyzes data and creates data visualizations and data tables.

## Rendered output

The rendered output can be found [here](https://kai-s-suzuki.github.io/ENVS-193DS_homework-03/code/homework.html)  
