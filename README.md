# IMDb Top 1000 Movies – Data Outputs

This repository contains cleaned datasets and summarized outputs derived from an analysis of the IMDb Top 1000 movies dataset using R. The project focuses on uncovering insights related to genre popularity, movie ratings, and box office performance.

##  Project Overview

The original dataset was cleaned and transformed in R using tidyverse tools. The cleaning process involved:
- Converting columns to appropriate data types (e.g., Runtime, Gross, IMDB_Rating)
- Removing missing or malformed data
- Parsing and formatting numerical fields

These cleaned and derived datasets were then exported for visualization and further use in portfolio web development.

##  Included Files

| File Name                 | Description                                      |
|--------------------------|--------------------------------------------------|
| imdb_clean.csv           | Fully cleaned dataset with all 1000 entries      |
| top_10_genre.csv         | Top 10 movie genres based on number of movies    |
| top_rating_genre.csv     | Average IMDb rating by genre (Top 10)            |
| top_10_gross.csv         | Top 10 highest grossing movies (by Gross value)  |
| rating_vs_gross.csv      | Dataset to explore correlation between rating and gross revenue |

##  Tools Used

- R / RStudio
- tidyverse (dplyr, readr, ggplot2)
- jsonlite (for JSON export)
- Data source: Kaggle / IMDb public dataset

##  Use Cases

These files are intended for:
- Portfolio web visualization (e.g. React + Chart.js or V0.dev)
- Public data storytelling
- Simple dashboard prototyping
- Resume-linked showcase project

##  Contact

Feel free to reach out if you'd like to collaborate or ask questions:

- Abdul Ghofur  
- Email: abdulpintar@gmail.com  
- Instagram: [@go_fury_](https://instagram.com/go_fury_)  
