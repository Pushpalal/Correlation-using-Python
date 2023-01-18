# Correlation-using-Python

This data was scraped from IMDb.
There are 7668 movies in the dataset from 1980 to 2020.

Each movie has the following attributes:

  budget: the budget of a movie. Some movies don't have this, so it appears as 0
  company: the production company
  country: country of origin
  director: the director
  genre: main genre of the movie.
  gross: revenue of the movie
  name: name of the movie
  rating: rating of the movie (R, PG, etc.)
  released: release date (YYYY-MM-DD)
  runtime: duration of the movie
  score: IMDb user rating
  votes: number of user votes
  star: main actor/actress
  writer: writer of the movie
  year: year of release

The objective is to find attributes which are highly correlated to gross collection of a movie.
