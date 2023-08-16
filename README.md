# AI-Academy-Semester-1-Capstone-Group-5 

## Source of Data
TO create our master dataframe, we used data from four different sources within the zippedData folder. These sources include:
1. IMBd (im.db.zip)
2. TMDb (tmdb.movies.csv.gz)
3. The Numbers (tn.movie_budgets.csv.gz)
4. Box Office Mojo (bom.movie_gross.csv.gz)

After combining and cleaning these datasets into one, we created our master dataframe. Our master dataframe includes the following:
- 3,122 rows
- 14 columns


## Description of Data

The master dataframe we created is used to represent the overall population. The index for the dataframe is "movie" which indicates that each row is organized based on movie. We decided to use the following columns in our master dataframe: studio, domestic_gross, foreign_gross, year, release_date, production_budget, worldwide_gross, averagerating, numvotes, runtime_minutes, genres, total_profit, runtime_bins, and rating_bins. Please see below for a description of the columns in our master dataframe:

- studio: the film studio that made the film
- domestic_gross: box office figures (in $) representing United States and Canada
- foreign_gross: box office figures (in $) not in the US or Canada
- year: the year representing a movie's respective domestic/foreign gross
- release_date: the date the film was released
- production_budget: the budget that is estimated to be the costs that are incurred from producing a film (in $)
- worldwide_gross: box office figures (in $) worldwide
- averagerating: average rating from a scale of 1-10
- numvotes: number of votes that is associated with the rating for a film
- runtime_minutes: duration of the film in minutes
- genres: genre/category of a film
- total_profit: difference between worldwide_gross and production budget (in $)
- runtime_bins: runtime_minutes placed in bins representing the duration of a film in hours
- rating_bins: averagerating placed in bins representing the average rating in bins from 1-9

