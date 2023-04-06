# Exploratory Data Analysis and Visualization of Films from 1980-2020

This project focuses on conducting exploratory data analysis and data visualization of films produced between 1980-2020. The project aims to analyze and explore the relationships between various features of the films, such as the genre, rating, budget, gross, director, writer, and runtime.

By conducting exploratory data analysis, we can identify trends, patterns, and relationships within the dataset, which can then be visualized using various data visualization techniques such as bar charts, scatter plots, and histograms. This will help to better understand the characteristics of the films produced during this period, and enable us to make predictions about future films.

> Dataset is from [Kaggle](https://www.kaggle.com/datasets/danielgrijalvas/movies)

## Question : How were the films selected?

Data Collector's answer : 

> First of all, the data was automatically scraped using a Python script, using IMDb's advanced search tool. Here's an example query using just the year and type of content (feature film):

> https://www.imdb.com/search/title?title_type=feature&release_date=1980-01-01,1980-12-31&count=100

> This returns 100 films from the year 1980, ordered by popularity. The script simply selects all those films, one by one, from top to bottom.

> That's the only criteria really, popularity.
