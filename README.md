# Speaker_Recommender
Speaker Recommender System

Behind every great live performance is a quality public address (PA) system of amplifiers and loudspeakers.
Since these systems are costly to implement, it is crucial that sound engineers and event planners choose
their equipment properly to maximize sound quality. The speaker recommender system uses a buyer's
prior experience with speakers to recommend new products, saving time and ensuring their money is well spent. 

## How it works (overview)

The recommender system holds a data frame of several different public address (PA) speaker products and their specifications. 
The user interacts with the system by providing/selecting a list of products which are liked and disliked based on prior experience. The recommender system will then return ranked lists of new similar products. 

In the background, the recommender system will map product specs to vectors in a high-dimensional feature space,
and compare available product vectors to a new vector constructed from the preferences.
To compare vectors, the system will use Euclidean or Cosine similarity distance measures between vectors. 
