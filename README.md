# Syndergaard_Research
I scraped Baseball Savant data in an attempt to develop a plan to improve Noah Syndergaard's pitching performance. 

### Setting the Proper Directory
In order to run the notebook, you must have the following files in the same folder:
* syndergaard_project.Rmd
* savant_data_2015-2020.csv

Once you have all the files in the same folder, open the R Notebook and set the correct working directory so that the files are accessible. You can do this by altering the following code to represent the path to the folder with the files:
`setwd('~/R/Projects/Syndergaard_Project')`

### Required Packages
The file also requires the following packages:
* tidyverse
* readxl
* lubridate
* baseballr

You can install the packages with the following code, replacing "package" with the package you would like to install:
`install.packages('package')`

Once the packages are installed, you should be able to run the code without any problems. Enjoy!
