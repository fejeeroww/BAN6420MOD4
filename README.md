# BAN6420MOD4
Assignment for module 4 assignment
# Netflix Data Analysis Project

This project analyzes the Netflix dataset, performing data cleaning, exploration, and visualization using both Python and R.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Prerequisites](#prerequisites)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Python Script](#python-script)
6. [R Integration](#r-integration)
7. [Output](#output)
8. [Data Cleaning Notes](#data-cleaning-notes)
9. [Troubleshooting](#troubleshooting)

## Project Overview

This project aims to analyze Netflix shows and movies data. It includes:
- Data preparation and cleaning
- Exploratory data analysis
- Visualization of key insights
- Integration of Python-generated visualizations into R

## Prerequisites

- Python 3.7+
- R 4.0+
- Required Python libraries: pandas, numpy, matplotlib, seaborn
- Required R packages: ggplot2, png

## Installation

1. Clone this repository or download the files.
2. Install required Python libraries: pandas numpy matplotlib seaborn
3. Install required R packages:
```r
install.packages(c("ggplot2", "png"))
Usage
Ensure the netflix_data.csv file is in the C:\Users\LADY FEJ\Module 4 assignment\ directory.
Run the Python script:
python netflix_analysis.py

Run the R script:
source("integrate_visualization.R")

Python Script
The netflix_analysis.py script performs the following tasks:

Renames the dataset
Cleans the data by addressing missing values
Performs data exploration
Creates visualizations
Saves the cleaned dataset
R Integration
The integrate_visualization.R script:

Reads the "Top 10 Genres" PNG file created by the Python script
Displays the visualization in R
Adds a title to the plot
Saves the integrated visualization as a new PNG file
Output
The scripts generate the following files in the C:\Users\LADY FEJ\Module 4 assignment\ directory:

Netflix_shows_movies.csv: The renamed dataset
Netflix_shows_movies_cleaned.csv: The cleaned dataset
type_distribution.png: Distribution of movies and TV shows
top_genres.png: Top 10 genres
rating_distribution.png: Distribution of ratings
top_genres_in_r.png: Top 10 genres visualization integrated into R
Data Cleaning Notes
Missing values in text columns are filled with 'Unknown'
The 'duration' column is handled specially due to mixed data types (e.g., '90 min', '1 Season')
The script standardizes the 'duration' format while preserving original information
Troubleshooting
If you encounter any issues:

Ensure all file paths are correct for your system
Check that you have the required Python libraries and R packages installed
Verify that the input CSV file is named correctly and in the right location
