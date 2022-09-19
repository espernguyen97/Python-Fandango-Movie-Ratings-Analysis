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

3. What tasks are given?

Through the data given, I'm looking for:

Task 1: The number of movies per year.

Task 2: Top 10 movies with the highest number of votes.

Task 3:  The difference between ratings that are displayed (STARS) versus what the true rating was from votes (RATING).

Task 4: Fandango Ratings vs Other Sites' scores

Task5: The number of worst movies rated across all platforms.

<hr>

Task 1: 

The number of movies per year.
<br>
<br>
 <img src="./img/task 1.png">
</p>
<br>
Task 2: 

Top 10 movies with the highest number of votes.
<br>
<br>
<img src="./img/task 2.png">
<br>
<br>
Task 3: 

The difference between ratings that are displayed (STARS) versus what the true rating was from votes (RATING).
<br>
<br>
<img src="./img/task 3.png">
<br>
<br>
Task 4: 

Fandango Ratings vs Other Sites' scores
<br>
<br>
<img src="./img/task 4.png">
<br>
<br>
<img src="./img/task 3.1.png">
<br>
<br>
Task : 

The number of worst movies rated across all platforms.
<br>
<br>
<img src="./img/task 5.png">
<br>
<br>
Conclusion:

