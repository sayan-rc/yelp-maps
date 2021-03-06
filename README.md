# Yelp Visual
Yelp Visual is a tool to visualize restaurant locations and ratings. In the example visualization below, nearby restaurants (dots) are grouped together using k-means clustering, where each color corresponds to a cluster. The map is segmented into regions (Voronoi diagram), where each region is shaded by the predicted rating of the closest restaurant (yellow = 5 stars, blue = 1 star). In this example, the user has a strong preference for southern restaurants, so the southern regions are colored yellow. Restaurants not rated by the user are given predicted ratings using least-squares linear regression and data of their past ratings and reviews from the Yelp Open Dataset.

![alt text](https://github.com/sayan-rc/yelp-visual/blob/master/visualize/voronoi.png?raw=true)
