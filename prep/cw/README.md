## Palmyra Ocean Health Index: Clean Waters

This folder describes the methods used to prepare the data layers for the Clean Waters goal. 


The folders in this file include the metadata, R scripts, and data for each assessement year (i.e., the year the assessment was conducted). The most current year represents the best available data and methods, and previous years are maintained for archival purposes. Each year folder contains the following files and sub-folders:     

- `debris_data_prep.Rmd` script to generate the status score for the marine debris layer   
- `soil_contamination_data_prep.Rmd` script to generate the status score for the soil contamination layer   
- `int` folder contains all intermediate files created by running through the `debris_data_prep.Rmd` and `soil_contamination_data_prep.Rmd` files    
- `output` folder with the layers generated in the script that are required to calculate the status score    
- `raw` folder contains debris data provided by The Nature Conservancy   

To learn more about how the Clean Waters goal is calculated, refer the project’s [Supplemental Methods](https://raw.githack.com/OHI-4site/pal-scores/master/documents/methods-results/Supplement.html) document.    





