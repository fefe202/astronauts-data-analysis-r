# Astronauts Data Analysis Project 🚀

This repository contains the final group project for the **Introduction to Data Analysis with R** course.

## Overview
The goal of this project is to perform a complete analytical workflow on the historical **Astronauts dataset**, provided by the [TidyTuesday initiative (2020-07-14)](https://github.com/rfordatascience/tidytuesday/tree/master/data/2020/2020-07-14). The dataset includes comprehensive information about astronauts, their missions, flight hours, and demographics.

## Authors
- Federico Di Franco
- Henry Michel Iannella Jones
- Francesco Pierri

## Project Structure
The analysis is entirely developed in an R Markdown file (`astronaut_database.Rmd`) and is divided into four main phases:

1. **✅ Data Cleaning and Preparation**: 
   - Loading the dataset directly from the source.
   - Checking data structure and handling missing values (`NA`).
   - Normalizing categorical variables (e.g., standardizing text to lowercase, fixing typos using regular expressions).
   - Transforming text data into factors for subsequent modeling.

2. **⏳ Exploratory Data Analysis (EDA)** *(In Progress)*: 
   - Descriptive statistics and correlation analysis.
   - Creation of new variables (e.g., aggregated values, indicators).
   - Data visualization using `ggplot2` to identify key patterns and trends.

3. **⏳ Statistical Modeling** *(Pending)*: 
   - Formulating research questions.
   - Building and comparing regression/classification models.
   - Interpreting coefficients and evaluating model quality.

4. **⏳ Summary and Reflection** *(Pending)*: 
   - Conclusions, limitations, and key findings.

## Tools & Libraries
The following R packages are required to run the code:
- `tidyverse` (for data manipulation and visualization)
- `janitor` (for initial name cleaning)
- `knitr` (for R Markdown rendering)

## How to run the code
1. Clone the repository.
2. Open the `astronaut_database.Rmd` file in RStudio.
3. Install the required packages if you don't have them (`install.packages(c("tidyverse", "janitor", "knitr"))`).
4. Click the **Knit** button in RStudio to generate the final HTML/PDF report.
