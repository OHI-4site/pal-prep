## Palmyra Ocean Health Index: Research 

This folder describes the methods used to prepare the data layers for the Research goal. 


The folders in this file include the metadata, R scripts, and data for each assessement year (i.e., the year the assessment was conducted). The most current year represents the best available data and methods, and previous years are maintained for archival purposes. Each year folder contains the following files and sub-folders:     

- `employment_data_prep.Rmd` script to generate the status score for the employment layers   
- `sci_papers_data_prep.Rmd` script to generate the status score for the scientific papers layer   
- `int` folder contains all intermediate files created by running through the `employment_data_prep.Rmd` and `sci_papers_data_prep.Rmd` files    
- `output` folder with the layers generated in the script that are required to calculate the status score    
- `raw` folder contains raw employment data and the Palmyra scientific library compiled by The Nature Conservancy   

To learn more about how the Research goal is calculated, refer the project's [Supplemental Methods](https://ohi-4site.github.io/pal-scores/documents/methods-results/Supplement.html) document.   






