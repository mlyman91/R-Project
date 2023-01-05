# Instructions for using R-Markdown File
1) Download the R-Markdown file (Chicago_Crime.Rmd) and save it to a folder on your machine.
2) Download the datasets below, and save them in the same folder as the .Rmd file in step 1.
    - [Chicago_All_Crime.zip](https://github.com/mlyman91/R-Project/blob/0177cddbca88cbff767e7b6a69eb7ed85edec24b/Chicago_All_Crime.zip) (unzip data files to folder titled "Chicago_All_Crime")
    - [Crime.zip](https://github.com/mlyman91/R-Project/blob/0177cddbca88cbff767e7b6a69eb7ed85edec24b/Crime.zip) (unzip data files to folder titled "Crime")
    - [Population.zip](https://github.com/mlyman91/R-Project/blob/0177cddbca88cbff767e7b6a69eb7ed85edec24b/Population.zip) (unzip data files to folder titled "Population")

# Data Sources & Info
## Crime.zip
Violent crime data provided to the FBI by each city. 
This information is used to compare violent crime rates across Chicago, New York City, Los Angeles, and the total United States.
Datasets can be found on the FBI's [Crime Data Explorer](https://cde.ucr.cjis.gov/LATEST/webapp/#/pages/explorer/crime/crime-trend) page.
<br />
<br />
The FBI introduced a new reporting platform in 2021, which resulted in many cities not reporting post 2020. 
As a result, we utilize data provided by the city of Chicago (Chicago_All_Crime) to analyze crime in 2021 and beyond.

## Chicago_All_Crime.zip
This file contains all violent crimes in 2018 and beyond. 
It was derived from Chicago's Public Crime data. 
If you would like to see the original source data, you can download it [here](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2).
However, please note the file is >1.7GB as of January 2023, and will grow as new data is added on a daily basis. See the "Load & Filter Chicago Source Data" section of the
.Rmd file for details on loading and manipulating the orignal source data.

## Population.zip
Population data is utilized to calculate per-capita crime statistics and can be found on [FRED's website](https://fred.stlouisfed.org/series/ILCOOK1POP).
The data in the zip file includes annual population estimates by county.
