## Palmyra Ocean Health Index: Habitats Sub-goal 

This folder describes the methods used to prepare the data layers for the Habitats sub-goal of the Biodiversity goal.     

The folders in this file include the metadata, R scripts, and data for each assessment year (i.e., the year the assessment was conducted). The most current year represents the best available data and methods, and previous years are maintained for archival purposes. Each year folder contains the following files and sub-folders:  

- `corals_data_prep.Rmd` script to generate the status score for the coral habitat   
- `coral_trend.Rmd` script to generate the trend in coral status   
- `rainforest_data_prep.Rmd` script to generate the status score for the rainforest habitat   
- `rainforest_trend.Rmd` script to generate the trend in rainforest status   
- `figs` folder containing maps and images from the data prep   
- `int` folder contains all intermediate files created by running through the `corals_data_prep.Rmd`, `coral_trend.Rmd`, `rainforest_data_prep.Rmd`, and `rainforest_trend.Rmd` files      
- `output` folder with the layers generated in the script that are required to calculate the status score    
- `raw` folder contains shapefiles from 2005 tree mapping surveys   

To learn more about how the Habitats sub-goal is calculated, refer the project’s [Supplemental Methods](https://ohi-4site.github.io/pal-scores/documents/methods-results/Supplement.html) document.   





