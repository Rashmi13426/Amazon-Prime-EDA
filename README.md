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

This project performs a comprehensive Exploratory Data Analysis (EDA) on Amazon Prime Video’s titles and credits datasets. The goal is to uncover actionable insights into:

* Content diversity – What genres dominate Prime?

* Regional strategy – How does availability differ across countries?

* Trends over time – How has Prime’s content evolved?

* Audience engagement – Which shows & movies stand out on IMDb ratings?

The project goes beyond visualization – it demonstrates data storytelling, business relevance, and analytical rigor.

---

## Key Features

* Structured EDA – Univariate, Bivariate, Multivariate analysis (UBM framework)
* 20+ Professional Visualizations – Histograms, Heatmaps, Line Charts, Scatterplots, Treemaps
* Business Insights – Every chart is linked to a real-world content strategy implication
* Well-documented Notebook – Clean, reproducible, and beginner-to-expert friendly
* End-to-End Workflow – Data cleaning → Analysis → Insights → Recommendations

---

## Key Insights with Supporting Charts from Amazon Prime EDA

1. Drama & Comedy are the most popular genres
* Chart: Bar plot of genre distribution.
2. United States contributes the highest number of titles
* Chart: Bar plot of top 10 countries by content count.
3. India is the second-largest contributor
* Chart: Same top 10 countries bar plot, highlighting India.
4. Most movies have a runtime between 90–120 minutes
* Chart: Histogram of movie durations.
5. IMDb ratings are concentrated between 6 and 8
* Chart: Histogram/KDE plot of IMDb ratings.
6. Movies dominate over TV shows
* Chart: Bar plot of content type distribution (Movies vs TV Shows).
7. Content releases increased sharply after 2015
* Chart: Line plot showing Trends Over Time.
8. IMDb Score & TMDb Score have the highest correlation (0.62) → indicates that ratings across platforms are strongly aligned.
* Chart: Correlation Heatmap.
9. Family/kids content (G, TV-Y, TV-Y7, TV-G) is very minimal (<2%).
* Chart: Pie chart of age certification
10. The volume of content released has changed annually. For example:
- A sharp rise post-2015 might suggest aggressive content acquisition.
- A dip in 2020 could reflect production delays due to COVID-19.
* Chart: Lineplot(Trends ove rtime)

---

## Technologies Used

- Python (Pandas, NumPy)
- Data Visualization: Matplotlib, Seaborn

## Visualizations

The project includes 20+ visualizations:

* Bar Charts (Genre distribution, Country comparison)

* Line Charts (Content growth over years)

* Heatmaps (Genre vs. Ratings)

* Pie Charts (Movies vs. TV shows)

* Treemaps (Content by region & genre)

* Scatterplots (IMDb ratings vs. popularity)

---
