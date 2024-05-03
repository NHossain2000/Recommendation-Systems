========================
Movie Recommender System
======================== 


Business Requirement:
---------------------
“MyNextMovie” is a budding startup in the space of recommendations on top of various OTT platforms providing suggestions to its customer base regarding their next movie.Their  major  business  is  to  create  a  recommendation  layer  on  top  of  these  OTT  platformsso that they can make suitable recommendations to their customers,however, since they are in research  mode  right  now,  they  would  want  to  experiment  with  open-source data first to understand the depth of the models which can be delivered by them.The data for this exercise is open-source data thathas been collected and made available from the MovieLens website(http://movielens.org), a part of GroupLensResearch The data sets were collected over various periods of time, depending on the size of the set.You have recently joined as a Data Scientist at “MyNextMovie” and plan to help the existing team to set up a recommendation platform.

Objective:

1.Create a popularity-based recommender system at a genre level. The userwill input a genre (g), minimum ratingthreshold (t) for a movie,and no. ofrecommendations(N) for which it should be recommended top N movies which are most popular within that genre (g) ordered by ratings in descending order where each movie has at least (t) reviews.

Example:Input:
•Genre (g) : Comedy
•Minimumreviewsthreshold(t):100
•Num recommendations (N) : 5


2.Create a content-based recommender system thatrecommends top N movies based on similar movie(m) genres.

Example:Input:
•Movie Title (t): Toy Story
•Num recommendations (N): 5

3.Create a collaborative based recommender system which recommends top N movies based on “K” similar users for a target user “u”

Example:Input:
•UserID:1
•Num recommendations(N): 5
•Threshold for similar users (k: 100Output:S.NoMovie Title1A2B3C4D5E

Data Description
----------------
The  data  consists  of  105339  ratings  applied  over  10329  movies.  The  average  rating  and minimum and maximum rating are 0.5 and 5 respectively. There are 668 users who have given their ratings for 149532 movies.There are two data files which are provided:Movies.csv
●movieId:IDassignedtoamovie
●title:Titleofamovie
●genres:pipe-separatedlistofmoviegenres.Ratings.csv
●userId:IDassignedtoauser
●movieId:IDassignedtoamovie
●rating:ratingbyausertoamovie
●Timestamp:timeatwhichtheratingwasprovided.

Steps and Tasks
---------------
●Import libraries and load dataset
●Exploratory Data Analysis including:oUnderstanding of distribution of the features availableoFinding unique users and moviesoAverage rating and Total movies at genre level.oUnique genres considered..
●Designthe3differenttypesofrecommendationmodulesasmentionedinthe objectives.
●Additional/Optional: Create a GUI interface using Python libraries(ipywidgetsetc.)to play around with the recommendation modules.


