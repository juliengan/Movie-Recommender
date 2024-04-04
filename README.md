# Movie-Recommender
- Process the user ratings with PySpark
- Collaborative filtering: algorithm ALS (Alternated Least Squares)
- KMeans to recommend unseen movies to users from preference clusters
- LinearRegression to predict box office revenues and average ratings

### Analysis of the ratings and movies
* Movies grouped by production names
* Movies ordered by popularity and other relevant insights
### Prediction of vote_averages and box office revenues thanks to a cross validator containing a RegressionEvaluator


### Recommendations of movies 

* Use of ALS to recommend N top movies from its users and predict users' ratings on movies they have not seen
* Use of KMeans to recommend clustered movies to clustered users 
