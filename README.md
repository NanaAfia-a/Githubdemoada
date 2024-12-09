Final-Project Project

Title: Investigating Binge Drinking and Its Relationship with Body Mass Index in Adults: A Cross-Sectional Analysis of the 2022 Behavioral Risk Factor Surveillance System

Description: This project examines the association between binge drinking and Body Mass Index (BMI) categories (underweight, normal weight, overweight, and obese) among adults aged 18–65 years and older in the United States. Using data from the 2022 Behavioral Risk Factor Surveillance System (BRFSS), the analysis evaluates how factors such as age, sex, race/ethnicity, physical activity, smoking status, and healthcare access influence this relationship. The study aims to provide insights into the intersection of alcohol consumption and obesity-related public health risks.

Features: Full analysis provided in a reproducible R Markdown file (analysis.Rmd). Includes data cleaning, visualization, and statistical modeling steps. Uses multiple imputation to handle missing data and ordinal logistic regression to analyze BMI predictors. Organized workflow and adherence to STROBE guidelines for reporting.

Contents analysis.Rmd: The R Markdown file containing all code, analyses, and visualizations. README.md: A guide to understanding and reproducing this project. LICENSE: Licensing information.

Requirements: To reproduce the analysis, ensure you have the following:

Software: R (version 4.4.1 or higher) RStudio

R Packages (loaded via pacman):

haven: For importing SPSS, Stata, or SAS data. readr: For reading tabular data. tidyverse: A collection of packages for data manipulation and visualization.

naniar and VIM: For exploring and handling missing data.

mice and lattice: For multiple imputations. table1: For creating descriptive tables.

DiagrammeR and rsvg: For visualizing flowcharts. dplyr: For data manipulation. car: For regression diagnostics.

Usage Clone the repository to your local machine: bash

Copy code git clone <https://github.com/NanaAfia-a/Githubdemoada.git> Open the analysis.Rmd file in RStudio.

Run the .Rmd file: Click Knit to generate an HTML or PDF report of the analysis and results. Alternatively, execute code chunks interactively to explore the workflow.

Results Key findings: Binge drinking was not significantly associated with BMI categories. Age was a strong predictor of BMI, with older adults more likely to have higher BMI. Women were more likely than men to fall into higher BMI categories Black Non-Hispanic individuals were less likely to have higher BMI compared to other racial/ethnic groups Physical activity had a protective effect, reducing the likelihood of higher BMI
