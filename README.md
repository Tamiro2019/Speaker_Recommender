# Speaker_Recommender
Speaker Recommender System

Behind every excellent live performance is a quality public address (PA) system of amplifiers and loudspeakers.
Since these systems are costly to implement, it is crucial that sound engineers, production managers, and event planners choose their equipment properly to ensure great sound quality. The speaker recommender system uses a buyer's
preferences to recommend new products, saving time and ensuring their money is well spent. 

## How it works (overview)

The recommender system holds a data frame of several different public address (PA) speaker products and their specifications. 
The user interacts with the system by providing/selecting a list of products which are liked and disliked based on prior experience. The recommender system will then return ranked lists of new similar products. 

In the background, the recommender system will map product specs to vectors in a high-dimensional feature space,
and compare available product vectors to a new vector constructed from the preferences.
To compare vectors, the system will use Euclidean or Cosine similarity measures between vectors. 

## Notebooks & Files

Check out the Speaker_Recommender.ipynb notebook to see how the recommender system works. 
The notebook includes:
* code that was used to scape Guitar Center for PA speaker product data.
* data cleaning and exploratory analysis
* the core of the recommendation system (using Euclidean and Cosine comparisson measure)
* preliminary validation analysis

The cvs files contain data used by the recommender system to build useful data frames. 

