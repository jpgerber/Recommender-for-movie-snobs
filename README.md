# Recommender-for-movie-snobs
This project developed and assessed metrics of movie snobbery to improve the accuracy of recommender systems. 
Working with the various stereotypes of snobs, I found that movie snobbery is best defined as an interest in older movies and obscure movies. Extremeness of ratings (like Statler & Waldorf in The Muppets) and being contrary to popular opinion are not good indicators of snobbery.
More importantly, preferences for obscure or older movies both improved the accuracy of a SVD++ recommender (RMSE 0.88) against the benchmark model (RMSE 0.90). Extremeness and contrariness (RMSE > 1) were less informative.

These findings might be applied to tweak recommender systems by allowing for a cooler-older-sibling/sage/guide function, a possibly more elegant solution to 'alt-right'/Star-Wars drift than direct content curation. Furthermore, these findings suggest the utility of psychological user profiling, an underutilized form of feature engineering.
