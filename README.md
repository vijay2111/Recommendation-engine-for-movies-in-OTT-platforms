# Recommendation-engine-for-movies-in-OTT-platforms
Data set consists of information about movies and the OTT platforms through which they are streamed

# Aim:
 * To create a recommendation system for the movies based on their similarities between the data points (Movies).
 * Recommendation system become vital for a business, where we need to keep customer engaged to the market.
 * Here, we tend to build content based recommendation engine on available data.

# Data Pre-processing
## Removing non informative features from the data.
 * ‘Age:’ There are about 57 % null values
 * ‘Rotten Tomatoes’: There are about 70 % null values
 * ‘Type’: Standard deviation is zero, thus add no value to the data frame

## Null Value Imputations.

# Data Language Processing
On a close investigation, information are scattered in terms of words in various features namely, 
 * Genres
 * Directors
 * Language and Country
To make above data to machine understandable information its necessary to process above features based on language processing  tools.
Here count_vectorizer is used to tokenize the count of  words in every record of particular feature.

# Recommendation System.
 * Here, trying to find similar record based on Cosine similarity

 * Each row is considered as a vector is get compared with all other vectors

 * From the array values, Particular Movie_Tittle’s recommendation Movie are fetched based on sorted similarity scores in descending order( ie., Similar data points have higher score )


