## Palmyra Ocean Health Index: Species Sub-goal 

This folder describes the methods used to prepare the data layers for the species sub-goal of the Biodiversity goal. 

The folders in this file include the metadata, R scripts, and data for each assessment year (i.e., the year the assessment was conducted). The most current year represents the best available data and methods, and previous years are maintained for archival purposes. Each year folder contains the following files and sub-folders:    

- `1_iucn_spp_list.Rmd` script to generate a list of species falling within 50 nm of Palmyra Atoll   
- `2_pal_spp_lists.Rmd` script that compiles TNC species lists and adds them to the IUCN species list      
- `3_spp_status.Rmd` scipt that generates the species status score   
- `4_spp_trend.Rmd` script that generates a trend in species status based on past IUCN assessments   
- `int` folder contains all intermediate files created by running through the `1_iucn_spp_lists.Rmd`, `2_pal_spp_lists.Rmd`, `3_spp_status.Rmd`, and `4_spp_trend.Rmd` files      
- `output` folder with the layers generated in the script that are required to calculate the status score    
- `raw` folder contains Palmyra fish and bird lists obtained from The Nature Conservancy, a species list pulled from the IUCN, and past IUCN risk codes.    

To learn more about how the Species sub-goal is calculated, refer the project’s [Supplemental Methods](https://ohi-4site.github.io/pal-scores/documents/methods-results/Supplement.html) document.   





