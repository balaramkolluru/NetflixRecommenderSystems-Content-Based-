# NetflixRecommenderSystems-Content-Based-

1. Business Problem

1.1 Problem Description

Netflix is all about connecting people to the movies they love. To help customers find those
movies, they developed world-class movie recommendation system: CinematchSM. Its job is to
predict whether someone will enjoy a movie based on how much they liked or disliked other
movies. Netflix use those predictions to make personal movie recommendations based on each
customer’s unique tastes. And while Cinematch is doing pretty well, it can always be made
better.

Now there are a lot of interesting alternative approaches to how Cinematch works that netflix
haven’t tried. Some are described in the literature, some aren’t. We’re curious whether any of
these can beat Cinematch by making better predictions. Because, frankly, if there is a much
better approach it could make a big difference to our customers and our business.

Credits: https://www.netflixprize.com/rules.html

1.2 Problem Statement

Netflix provided a lot of anonymous rating data, and a prediction accuracy bar that is 10% better
than what Cinematch can do on the same training data set. (Accuracy is a measurement of how
closely predicted ratings of movies match subsequent actual ratings.)

1.3 Real world/Business Objectives and constraints

Objectives:
1. Predict the rating that a user would give to a movie that he ahs not yet rated.
2. Minimize the difference between predicted and actual rating (RMSE and MAPE)

Constraints:
1. Some form of interpretability

2. Machine Learning Problem

2.1.1 Data Overview
Get the data from : https://www.kaggle.com/netflix-inc/netflix-prize-data/data
Data files :
combined_data_1.txt
combined_data_2.txt
combined_data_3.txt
combined_data_4.txt
movie_titles.csv
</ul>
