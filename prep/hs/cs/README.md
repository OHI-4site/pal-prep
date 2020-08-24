## Palmyra Ocean Health Index: Carbon Storage Sub-goal 

This folder describes the methods used to prepare the data layers for the carbon storage sub-goal of the Habitat Services goal. 

The folders in this file include the metadata, R scripts, and data for each assessment year (i.e., the year the assessment was conducted). The most current year represents the best available data and methods, and previous years are maintained for archival purposes. Each year folder contains the following files and sub-folders:  

- `carbon_storage_data_prep.Rmd` script to generate the status score for carbon storage   
- `carbon_storage_trend.Rmd` script to generate the trend for the carbon storage sub-goal   
- `int` folder contains all intermediate files created by running through the `carbon_storage_data_prep.Rmd` and `carbon_storage_trend.Rmd` files      
- `output` folder with the layers generated in the script that are required to calculate the status score    
- `raw` folder containing vegetation mapping shapefiles      

To learn more about how the Carbon Storage sun-goal is calculated, refer the project’s [Supplemental Methods](https://raw.githack.com/OHI-4site/pal-scores/master/documents/methods-results/Supplement.html) document.    





