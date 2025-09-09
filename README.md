## Amazon Prime Dataset

This project includes sample datasets related to Amazon Prime Video content, consisting of the following files:

- `titles.csv`: Contains details about Amazon Prime Video titles such as movies and TV shows.
- `credits.csv`: Contains information about the cast and crew for each title.

### Dataset Description:
- **titles.csv** columns include: 'id',	'title',	'type',	'description', 'release_year', 'age_certification',	'runtime',	'genres',	'production_countries',	'seasons',	'imdb_id',	'imdb_score',	'imdb_votes',	'tmdb_popularity',	'tmdb_score'

- **credits.csv** columns include: 'person_id',	'id', 	'name',	'character',	'role'

# Amazon Prime Video EDA

Welcome to my Data Analysis project focused on Amazon Prime Video content! This project provides a thorough exploratory data analysis (EDA) of the highest-rated titles available on Amazon Prime, aiming to uncover actionable insights into content performance, ratings, and popularity trends.

---

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a dataset of Amazon Prime Video titles, analyzing relationships between various features such as IMDb ratings, TMDb ratings, vote counts, and content popularity.  
The goal is to provide meaningful insights to support data-driven decisions on content strategy, marketing, and platform growth.

---

## Key Features

- Data cleaning and preprocessing
- Visualizations:  
  - Bar plot for top 10 highest-rated titles  
  - Pair plot to analyze correlations between key numerical variables  
- Insightful analysis of ratings vs. popularity  
- Identification of key data patterns and outliers

---

## Sample Insights

- Positive correlation between IMDb and TMDb scores suggests consistency across rating platforms.
- Popularity and ratings are not strongly correlated, implying high-rated content is not necessarily most watched.
- Visualization helped identify outliers and voting patterns across titles.
- Data quality and missing value handling improved overall data reliability.

---

## Technologies Used

- Python (Pandas, NumPy)
- Data Visualization: Matplotlib, Seaborn
- Jupyter Notebook for interactive data analysis

