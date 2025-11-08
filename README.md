# Multivariate Data Analysis Project

This project performs a multivariate data analysis on a dataset of US cities, focusing on pollution and other environmental factors. The primary methods used are Principal Component Analysis (PCA) and Cluster Analysis.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

To run this project, you will need:

*   **R**: A free software environment for statistical computing and graphics. You can download it from [CRAN](https://cran.r-project.org/).
*   **RStudio (Recommended)**: An integrated development environment (IDE) for R. You can download it from [RStudio](https://www.rstudio.com/products/rstudio/download/).
*   **Git**: For cloning the repository.

### Cloning the Repository

To get a copy of the project, open your terminal (Linux/macOS) or Git Bash (Windows) and run the following command:

```bash
git clone https://github.com/your-username/pca_analysis.git
cd pca_analysis
```

Replace `https://github.com/your-username/pca_analysis.git` with the actual URL of this repository.

### Folder Structure

The project has the following structure:

```
pca_analysis/
├── Multivariate_Data_Analysis_Project/
│   ├── data/
│   │   └── data_5.csv
│   ├── Multivariate_Data_Analysis_Project.Rmd
│   ├── Multivariate_Data_Analysis_Project.html
│   └── Project_guidelines_25_26.pdf
└── README.md
```

*   `Multivariate_Data_Analysis_Project/`: This directory contains the core project files.
    *   `data/`: This directory stores the dataset used for the analysis.
        *   `data_5.csv`: The dataset containing pollution and environmental factors for US cities.
    *   `Multivariate_Data_Analysis_Project.Rmd`: The R Markdown file containing the R code for the analysis and the project narrative.
    *   `Multivariate_Data_Analysis_Project.html`: The rendered HTML output of the R Markdown file, presenting the analysis results.
    *   `Project_guidelines_25_26.pdf`: The project guidelines document.
*   `README.md`: This file provides an overview of the project and instructions for setup and usage.

## Running the Analysis

1.  **Open the Project in RStudio**:
    *   Launch RStudio.
    *   Go to `File > Open File...` and navigate to `Multivariate_Data_Analysis_Project/Multivariate_Data_Analysis_Project.Rmd` and open it.

2.  **Install Required Packages**:
    *   The R Markdown file might require certain R packages. If you encounter errors about missing packages, install them using the following command in the RStudio console:
        ```R
        install.packages("ggplot2") # Example: install ggplot2 if needed
        ```
        (You may need to install other packages as indicated by error messages when knitting.)

3.  **Run the R Markdown File**:
    *   In RStudio, with `Multivariate_Data_Analysis_Project.Rmd` open, click the "Knit" button (usually found in the toolbar, looks like a ball of yarn with a needle) to knit the document to HTML. This will execute all the R code chunks and generate the `Multivariate_Data_Analysis_Project.html` file, which contains the full analysis and results.

## Data Description

The `data_5.csv` dataset contains the following variables:

*   **so2**: Sulfur dioxide content of air in micrograms per cubic meter
*   **temp**: Average annual temperature (F)
*   **manuf**: No. of manufacturing enterprises employing 20 or more workers
*   **pop**: Population size (1970 census) in thousands
*   **wind**: Average wind speed in miles per hour
*   **precip**: Average annual precipitation in inches
*   **days**: Average number of days with precipitation per year (annual average number of days of rain)

## Contributing

Please read `Project_guidelines_25_26.pdf` for detailed contribution guidelines.

## License

This project is licensed under the [MIT License](LICENSE) - see the LICENSE.md file for details. (Note: A `LICENSE.md` file is not currently present in the repository. This is a placeholder.) 