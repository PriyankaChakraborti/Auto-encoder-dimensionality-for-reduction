# Auto-encoder-dimensionality-reduction
Using a simple linear auto encoder to learn hidden representation of a 11 dimensional coffee data set in 5 dimensions.

Approximately 4GB of coffee shop data from Yelp were scraped and then munged using their location boundary data from Zillow.

Following this I combined the data into domain based features on which I performed PCA. The hidden layer of the auto encoder was then used to project the feature matrix to 5 dimensions.
Also includes a stacked auto encoder for Mnist digits recognition

This repository contains the code used for the auto-encoding portion of this analysis.
