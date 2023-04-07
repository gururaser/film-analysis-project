# Exploratory Data Analysis and Visualization of Films from 1980-2020

This project focuses on conducting exploratory data analysis and data visualization of films produced between 1980-2020. The project aims to analyze and explore the relationships between various features of the films, such as the genre, rating, budget, gross, director, writer, and runtime.

By conducting exploratory data analysis, we can identify trends, patterns, and relationships within the dataset, which can then be visualized using various data visualization techniques such as bar charts, scatter plots, and histograms. This will help to better understand the characteristics of the films produced during this period, and enable us to make predictions about future films.

> Dataset is from [Kaggle](https://www.kaggle.com/datasets/danielgrijalvas/movies)

# You may want to take a look at the report.

[Data Analysis Report (PDF)](https://github.com/gururaser/film-analysis-project/blob/main/data-analysis-of-movie-industry-report.pdf)

## Question : How were the films selected?

Data Collector's answer : 

> First of all, the data was automatically scraped using a Python script, using IMDb's advanced search tool. Here's an example query using just the year and type of content (feature film):

> https://www.imdb.com/search/title?title_type=feature&release_date=1980-01-01,1980-12-31&count=100

> This returns 100 films from the year 1980, ordered by popularity. The script simply selects all those films, one by one, from top to bottom.

> That's the only criteria really, popularity.


## In which range of IMDb scores are movies most commonly rated?

![Analysis](https://github.com/gururaser/film-analysis-project/blob/main/number_of_movies_by_imdb_score_range.jpg)


## Which genres have the highest average ratings?

![Analysis](https://github.com/gururaser/film-analysis-project/blob/main/avg_imdb_score.jpg)
![Analysis](https://github.com/gururaser/film-analysis-project/blob/main/avg_imdb_score_errorbars.jpg)
![Analysis](https://github.com/gururaser/film-analysis-project/blob/main/avg_imdb_score_filtered_genres.jpg)

## How is the distribution of movie releases across years? Is there an increase or decrease in specific genres during a particular period?

![Analysis](https://github.com/gururaser/film-analysis-project/blob/main/movie_releases_by_year_genre.jpg)

## What is the relationship between budget and revenue? Do high-budget films generate higher revenues?

![Analysis](https://github.com/gururaser/film-analysis-project/blob/main/budget_gross_scatterplot.jpg)
![Analysis](https://github.com/gururaser/film-analysis-project/blob/main/budget_gross_lmplot.jpg)

## Is there a relationship between the duration of films and their ratings, budgets, and revenues?

![Analysis](https://github.com/gururaser/film-analysis-project/blob/main/runtime_score_budget_gross_heatmap.jpg)

## What are the director-star pairs that have collaborated the most, have the highest average IMDb score, and have earned the most revenue together?

![Analysis](https://github.com/gururaser/film-analysis-project/blob/main/star_director_num_of_movies.jpg)
![Analysis](https://github.com/gururaser/film-analysis-project/blob/main/star_director_avg_imdb_score.jpg)
![Analysis](https://github.com/gururaser/film-analysis-project/blob/main/star_director_total_gross.jpg)

## Which companies earned the most revenue?

![Analysis](https://github.com/gururaser/film-analysis-project/blob/main/top_6_companies_gross.jpg)

## How many films were released in each season? How did the revenues of the films vary by the season they were released in?

![Analysis](https://github.com/gururaser/film-analysis-project/blob/main/number_of_movies_by_season.jpg)
![Analysis](https://github.com/gururaser/film-analysis-project/blob/main/total_gross_revenue_by_season.jpg)
![Analysis](https://github.com/gururaser/film-analysis-project/blob/main/distribution_of_box_office_revenue_by_season.jpg)

## Which actors have appeared in the most films?

![Analysis](https://github.com/gururaser/film-analysis-project/blob/main/top_10_actors_by_number_of_movies.png)
