![picture alt](http://i.imgur.com/OlYzwSW.jpg "README-Picture")
Synopsis
=============
This exercise uses a dataset from IMDb ranging from age 1893 to 2005. Your tasks is to analyze the data and draw conclusion with your results(Think historicaly).

CSV File
-------
The CSV file can be found in the on this github link. Use the CSV file attached so every group analyzes the same data.
The CSV file contains the following headers:
* title `Title of the movie`
* year `Year the movie was released`
* length `Length of the movie in minutes`
* budget `Cost of the movie`
* rating `The average rating(Rating listed on IMDb)`
* votes `Amount of votes given`
* r1-r10 `Possibility of rating given from 1 Rating to 10 Rating. Should add up to 100, but due to rounding it doesnot sum up exactly`
* mpaa(Motion Picture Association of America) `https://en.wikipedia.org/wiki/Motion_Picture_Association_of_America_film_rating_system`
* Genres(Action,Animation,Comedy,Drama,Documentary,Romance,Short) `Which genre the film is(Can be multiple)`  

Questions
-------
1. Create histograms of rating, year, length and length of title.
2. Create a graph showing both year and amount of movies made. 
3. Make a scatter-plot with year and length of movies. (Try to find clusters and explain them. Wild guesses are accepted).
4. Apply the KMeans algorithm to identify all the clusters in the scatter-plot from Question 3. 
5. Create a median line for the scatter-plot made in Question 3.
6. Make a scatter plot of: Length,year and if the movie is animated or not. Explain the connections between the different axis.
