# Netflix Content Performance Analysis

An exploratory analysis of a 100-title Netflix dataset using R to examine differences in audience reach, ratings and viewership consistency across content genres.

## Project Overview

This project demonstrates a practical data analysis workflow in R, including data importing, cleaning, validation, transformation, joins and grouped descriptive analysis.

The analysis explores three main questions:

- Which genres generate the highest average viewership?
- Which genres receive the highest audience ratings?
- How consistent is viewership within each genre?

## Tools & Techniques

- R
- readr
- dplyr
- Data cleaning and validation
- Data transformation
- Joins
- Grouped descriptive statistics
- Audience and content performance analysis

## Key Findings

**Documentary** recorded the highest average viewership at approximately **155.05 million views**, followed closely by Sci-Fi at **153.12 million**.

**Thriller** achieved the highest average audience rating at approximately **7.66**, despite ranking sixth for average viewership.

Documentary also recorded the lowest viewership standard deviation at approximately **57.24 million**, indicating comparatively consistent audience reach within the sample.

The results demonstrate that **audience reach and audience ratings represent different dimensions of content performance**.

## Dataset

The analysis uses a dataset containing:

- 100 titles
- 9 variables
- 7 genres
- 0 missing values

The findings relate only to the 100-title dataset analysed and should not be interpreted as representative of Netflix's complete catalogue.

## Files

- `netflix-content-analysis.Rmd` — R Markdown analysis and methodology
- `netflix-content-analysis.html` — rendered analysis report
- `netflix_dataset.csv` — dataset used in the analysis
