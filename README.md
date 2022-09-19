Fandango's Movie Ratings Analysis

## Overview

If we are planning on going out to see a movie, how well can we trust online reviews and ratings? *Especially* if the same company showing the rating *also* makes money by selling movie tickets. Do they have a bias towards rating movies higher than they should be rated?

1. Understanding the Background and Data


**The article: [Be Suspicious Of Online Movie Ratings, Especially Fandango’s](http://fivethirtyeight.com/features/fandango-movies-ratings/)**

### The Data

This is the data behind the story [Be Suspicious Of Online Movie Ratings, Especially Fandango’s](http://fivethirtyeight.com/features/fandango-movies-ratings/) openly available on 538's github: https://github.com/fivethirtyeight/data. There are two csv files, one with Fandango Stars and Displayed Ratings, and the other with aggregate data for movie ratings from other sites, like Metacritic,IMDB, and Rotten Tomatoes.

#### all_sites_scores.csv

-----

`all_sites_scores.csv` contains every film that has a Rotten Tomatoes rating, a RT User rating, a Metacritic score, a Metacritic User score, and IMDb score, and at least 30 fan reviews on Fandango. The data from Fandango was pulled on Aug. 24, 2015.


Column | Definition
--- | -----------
FILM | The film in question
RottenTomatoes | The Rotten Tomatoes Tomatometer score  for the film
RottenTomatoes_User | The Rotten Tomatoes user score for the film
Metacritic | The Metacritic critic score for the film
Metacritic_User | The Metacritic user score for the film
IMDB | The IMDb user score for the film
Metacritic_user_vote_count | The number of user votes the film had on Metacritic
IMDB_user_vote_count | The number of user votes the film had on IMDb

2. Goal:

Determine if Fandango's ratings in 2015 had a bias towards rating movies better to sell more tickets based off the 538 article and the data

3. What tasks ar given?

Through the data given, I'm looking for:

Task 1: The relationship between popularity of a film and its rating and votes.

Task 2: The number of movies per year.

Task 3: Top 10 mmovies with the highest number of votes.

Task 4:  The difference between ratings that are displayed (STARS) versus what the true rating was from votes (RATING).

Task 5: Fandango Ratings vs Other Sites' scores

Task 6: The number of worst movies rated across all platforms.

