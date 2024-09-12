# BAN6420 MODULE 4 ASSIGNMENT (Using a jupyter notebook)
Assignment for module 4 assignment
# Analyzing Netflix Dataset
This Jupyter Notebook project analyzes the Netflix dataset, performing data cleaning, exploration, and visualization using Python, with an additional step to integrate a visualization into R.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Prerequisites](#prerequisites)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Notebook Contents](#notebook-contents)
6. [Output](#output)
7. [R Integration](#r-integration)
8. [Data Cleaning Notes](#data-cleaning-notes)
9. [Troubleshooting](#troubleshooting)

## Project Overview

This assignment uses a Jupyter Notebook to analyze Netflix data. It includes:
- Data preparation and cleaning
- Data Exploratory
- Visualization
- Integration of a Python-generated visualization into R

## Prerequisites

- Python 3.7+
- Jupyter Notebook
- R 4.0+ (for visualization integration)
- Required Python libraries: pandas, numpy, matplotlib, seaborn
- Required R packages: ggplot2, png

## Installation

1. Download the files.
2. Install required Python libraries:jupyter pandas numpy matplotlib seaborn
3. Install required R packages (in R or RStudio): ```r
    install.packages(c("ggplot2", "png"))

Usage

1. The netflix_data.csv file is in the C:\Users\LADY FEJ\Module 4 assignment\ directory.
2. Launch Jupyter Notebook: jupyter notebook
3. Open the ipynb notebook file in the zipfile.
4. Run all cells in the notebook sequentially.

Notebook Contents

The Jupyter Notebook ipynb file contains the following sections:

1. Data Loading and Preparation
2. Data Cleaning
3. Data Exploratory
4. Data Visualization
5. Saving Cleaned Data and Visualizations
6. R Integration Code (to be run separately in R)


Output

The notebook generates the following files in the C:\Users\LADY FEJ\Module 4 assignment\ directory:

Netflix_shows_movies.csv: The renamed dataset
Netflix_shows_movies_cleaned.csv: The cleaned dataset
type_distribution.png: Distribution of movies and TV shows
top_genres.png: Top 10 genres
rating_distribution.png: Distribution of ratings


R Integration

To integrate the "Top 10 Genres" visualization into R:

Run the R code in the last cell of the notebook in an R environment.
This will create top_genres_in_r.png in the project directory.


Data Cleaning Notes

Missing values in text columns are filled with 'Unknown'
The 'duration' column is handled specially due to mixed data types (e.g., '90 min', '1 Season')
The notebook standardizes the 'duration' format while preserving original information


Troubleshooting

If you encounter any issues:

Ensure all file paths are correct for your system
Check that you have the required Python libraries and R packages installed
Verify that the input CSV file is named correctly and in the right location
Make sure you're running the notebook cells in order
