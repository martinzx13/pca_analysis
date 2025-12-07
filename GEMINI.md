## Directory Overview

This directory contains a multivariate data analysis project for a university course. The goal of the project is to analyze a dataset of pollution in 41 US cities using Principal Component Analysis (PCA) and cluster analysis.

The directory is organized as follows:

*   `code/`: Contains the R Markdown file with the analysis.
*   `data/`: Contains the dataset in CSV format.
*   `guidelines/`: Contains the project guidelines.
*   `report/`: Contains the final HTML report.

## Key Files

*   `code/Multivariate_Data_Analysis_Project.Rmd`: The main R Markdown file containing the data loading, preprocessing, PCA, and visualization.
*   `data/data_5.csv`: The dataset with 7 variables for 41 US cities. The variables are:
    *   `so2`: Sulfur dioxide content
    *   `temp`: Average annual temperature
    *   `manuf`: Number of manufacturing enterprises
    *   `pop`: Population size
    *   `wind`: Average wind speed
    *   `precip`: Average annual precipitation
    *   `days`: Average number of days with precipitation
*   `report/Multivariate_Data_Analysis_Project.html`: The HTML report generated from the R Markdown file. This file contains the full analysis and visualizations.
*   `guidelines/Project_guidelines_25_26.txt`: A text file with the project guidelines, including the tasks to be performed.

## Usage

The analysis is performed by running the `code/Multivariate_Data_Analysis_Project.Rmd` file in an R environment (like RStudio). This will generate the `report/Multivariate_Data_Analysis_Project.html` file.

To run the analysis, you need to have R and the following R libraries installed:

*   `knitr`
*   `ggplot2`
*   `devtools`
*   `ggbiplot`
*   `plotly`

You can then open the Rmd file and run all chunks to reproduce the report.