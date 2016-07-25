Your competitor, MovieCo, has an open API which allows you to see their last 10,000 rentals. In order to get a competitive advantage, your job is to write some code to analyze that data and spot trends.

The API is available at two endpoints:

* http://159.203.175.239:8080/movies.txt

Contains all of the movies in the format

	ID Title (Year)

Example

	111 Good Will Hunting (1997)

	(The movie "Good Will Hunting" from 1997 has id 111)

* http://159.203.175.239:8080/checkouts.txt

Contains the last 12 months of checkouts in the format

	userID Month MovieID

Example

	user95 jun 83

	(The user #95 checked out movie #83 in June)

	Each record in checkouts.txt records one instance of one movie being checked out by one user.

Your job is to write code to answer the following questions:

1. What user(s) had the most checkouts?

2. What month(s) had the most checkouts?

3. What is the title of the movie(s) that was the most checked out?