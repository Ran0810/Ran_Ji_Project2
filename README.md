# Ran Ji Project 2

This repository contains all files for Project 2 of R 721.

# Contents
- `Ran_Ji_Project2.Rmd` — The full R Markdown analysis.
- `Ran_Ji_Project2.docx` — The Word file generated from the Rmd.
- `data/` — Folder containing the air quality data for 2018–2020.
- `Ran_Ji_Project2.Rproj` — RStudio project file.

# GitHub Link
https://github.com/Ran0810/Ran_Ji_Project2

# Project Summary
This project processes EPA air pollution data (CO, PM2.5, O3) from 2018–2020
and performs exploratory data analysis (EDA).  
A custom function was created to clean each dataset:
- rename variables  
- fix date formats  
- handle duplicate days  
- average multiple daily measurements  
- correct negative values  

Two plots summarize trends:
1. CO & O3 monthly averages (2018–2020 combined)
2. PM2.5 monthly averages by year

# How to Run
Open the `.Rproj` file in RStudio and knit the `.Rmd` document.
