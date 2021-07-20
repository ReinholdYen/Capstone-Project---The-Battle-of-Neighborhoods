# Introduction/Business Problem

The goal of this project is to recommend a location for someone looking to open a restaurant in New York City.
We will work on answering the following questions:

1. Where are the popular locations for running a restaurant business? Are there any geographical patterns in these popular restaurants?
    To find the hottest spot, we search restaurants from Foursquare location data. Then cluster these restaurants and locate the center of each cluster. 

2. How many times do these restaurants be mentioned by users of Foursquare?
    To confirm whether or not the hottest spot is the most popular one, we get the tips number of these restaurants from Foursquare to see the correlation between location and popularity.

3. Are there any patterns in the locations of these popular restaurants?
    Finally, we cluster restaurants by their nearby venues data, then discuss the characteristics of each cluster.

# Data

To answer the first question, we use the latitude and longitude data of the restaurants from Foursquare. Cluster the restaurants based on their locations. Then get the center of each cluster.

To see whether or not the restaurant closer to the center of each cluster is more popular, we use the tips number of each restaurant from Foursquare. Also, divide the restaurants into different levels of the tips number.

To look for any subtle patterns in the locations of the restaurants, we use the nearby venues' data to cluster the restaurants. For example, use the nearby venue's category as the feature for clustering.
