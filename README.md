# An Introduction to Tidy R Spatial Packages: Incorporating Historic Sociodemographic Data from the US Census and Visualizing Geographic Distributions


## 1. Overview

This repository contains an introductory demo to using spatial packages in R, prepared for the R Medicine 2024 conference. The demo will walk you through downloading Census data, merging in health data, exploring the data with summary statistics, and creating geographic maps to explore geographic distributions of the variables. 

## 2. Folder Structure

We have organized relevant files in the following folders: 

- `code`: Code for the demo 
- `data`: Health data needed for the demo
- `images`: Supportive images for the demo

## 3. Data Sources

We used two primary data sources for the following features in this demo: 

- [U.S. American Community Survey, 2017-2021 5-year estimates](https://www.census.gov/data/developers/data-sets/acs-5year.2021.html): sociodeconomic variables
  - Request a U.S. Census API key [here](https://api.census.gov/data/key_signup.html) 

- [U.S. Centers for Disease Control and Prevention PLACES, 2023](https://data.cdc.gov/500-Cities-Places/PLACES-Local-Data-for-Better-Health-Census-Tract-D/cwsq-ngmh/about_data): CHD prevalence

## 4. Requirements

You will need the following software, R packages, and data to complete the demo.

### 4.1 Software and R Packages

1.  Download the following software:

-   [R](https://cran.r-project.org/bin/windows/base/)
-   [RStudio](https://www.rstudio.com/products/rstudio/download/#download) or another R graphical user interface

2.  Run the following code in R to install the following packages:

`install.packages(c('tidyverse','tidycensus','readr','sf','ggspatial','patchwork'), dependencies = TRUE)`

3.  We used the following versions of software and packages:

-   **Software**:
    -   *R:* 4.2.2 ("Innocent and trusting")
    -   *RStudio:* 2024.04.1+748 ("Chocolate Cosmos")
-   **Packages**:
    -   *`tidyverse`:* 1.3.2
    -   *`tidycensus`:* 1.3.2
    -   *`readr`:* 2.1.3
    -   *`sf`:* 1.0.9
    -   *`ggspatial`:* 1.1.9
    -   *`patchwork`:* 1.2.0

### 4.2 Data

-   U.S. Centers for Disease Control and Prevention PLACES 2020
    -   Download [here](https://chronicdata.cdc.gov/500-Cities-Places/PLACES-Local-Data-for-Better-Health-Place-Data-202/q8xq-ygsk).
-   U.S. American Community Survey, 5-year estimates from 2017-2021
    -   To download the data, refer to our code: `code/demo-rspatial.Rmd`


## 5. Cloning this Repository with RStudio

Below are steps to clone this repository to your local device with RStudio. Please refer to this [link](https://resources.github.com/github-and-rstudio/) for more information about using git in RStudio.

1.  On top this page, click on `Code` and copy the link to this git repository (starts with <https://github.com/>...).
2.  Open RStudio.
3.  In RStudio, click on `File` → `New Project...` → `Version Control` → `Git`.
4.  Under "Repository URL", paste the link of the git repository.
5.  Under "Project directory name", name your project directory.
6.  Under "Create project as subdirectory of:", select the folder in which you would like your project directory to be located.
7.  Click on `Create Project` when you are done to clone your repository!



