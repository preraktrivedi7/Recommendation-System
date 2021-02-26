# Recommendation System
 Netflix Movie Recommendation System

## Netflix Movie Recommendation System
Netflix is a streaming service which is all about connecting people to the movies, TV series and drama they love. Moreover, Netflix is loved by the customers because of the recommendation system (CinematchSM) that it developed. It predicts whether the user will enjoy the movie based on the previous genres of movie they liked. Netflix use those predictions to make personal movie recommendations based on each customer’s unique tastes. Here is a small attempt to improvise [CinematchSM](http://savantemeritus.files.wordpress.com/2011/07/values-in-technology-sp2011-final-paper-gayle-gatchalian-final.pdf).

There are multiple techniques that can be applied of which some are based on research and a few are applied. However, even a small improvement in the result can be helpful as it can generate better customer response.

Project Idea Collected from [Netflix Prize](https://www.netflixprize.com).

Link to Dataset: https://www.kaggle.com/netflix-inc/netflix-prize-data


## Real world/Business Objectives and constraints 
### Objectives:
1. Predict the rating that a user would give to a movie that he has not yet rated.
2. Minimize the difference between predicted and actual rating (RMSE and MAPE) 

### Constraints:
1. Some form of interpretability.
2. There is no low latency requirement as the recommended movies can be precomputed earlier.

## Type of Data:
* There are 17770 unique movie IDs.
* There are 480189 unique user IDs.
* There are ratings. Ratings are on a five star (integral) scale from 1 to 5.
* There is a date on which the movie is watched by the user in the format YYYY-MM-DD.


## Basic Libraries
*	Python Notebook
*	Scikit-learn
*	seaborn, matplotlib
*	numpy, scipy
*	pandas
*   XGBoost