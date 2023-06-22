# Analysis of Black Friday Dataset

## Problem Statement
The goal of this analysis is to understand consumer behavior during Black Friday by examining sales data. The dataset used for this analysis was obtained from Kaggle and contains information about user demographics, product details, and purchase history.

## Dependencies and Requirements
To run the analysis code, the following dependencies are required:
* R programming language
* Tidyverse package
* ggplot2 package

## Installation and Usage
1. Install R: Visit the official R website (https://www.r-project.org/) and follow the instructions to install R on your computer.
2. Install Tidyverse and ggplot2 packages: Open R console or an R script editor and run the following commands:
```
install.packages("tidyverse")
install.packages("ggplot2")
```
3. Download the Black Friday dataset:
* Go to the Kaggle website (https://www.kaggle.com/llopesolivei/blackfriday#).
* Click on the "Download" button to download the dataset.
* Save the downloaded CSV file ("BlackFriday.csv") in your desired location.
4. Load the dataset and run the analysis code: Open an R script editor or RStudio and execute the following code:
```
suppressPackageStartupMessages(library(tidyverse))
# Set the file path to the downloaded dataset
file_path <- "path/to/BlackFriday.csv"
# Load the dataset
blackfriday <- read_csv(file_path, show_col_types = FALSE)
# Perform the analysis
# ... (Copy and run the analysis code provided in your question)
```
5. View the analysis results: After running the analysis code, you will be able to see the generated graphs and explore the insights derived from the data.
