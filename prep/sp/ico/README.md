## Palmyra Ocean Health Index: Iconic Species Sub-goal 

This folder describes the methods used to prepare the data layers for the iconic species sub-goal of the Sense of Place goal.     

The folders in this file include the metadata, R scripts, and data for each assessment year (i.e., the year the assessment was conducted). The most current year represents the best available data and methods, and previous years are maintained for archival purposes. Each year folder contains the following files and sub-folders:  

- `ico_data_prep.Rmd` script to generate the status scores for iconic species   
- `ico_fxn.R` functions to assist with calculating the iconic species status scores   
- `int` folder contains all intermediate files created by running through the `ico_data_prep.Rmd` file   
- `output` folder containing layers generated in the script that are necessary to calculate the goal score     
- `raw` folder contains raw data of species lists compiled from USFWS or pulled from the IUCN   

To learn more about how the Iconic Species sub-goal is calculated, refer the project's [Supplemental Methods](https://ohi-4site.github.io/pal-scores/documents/methods-results/Supplement.html) document.   






