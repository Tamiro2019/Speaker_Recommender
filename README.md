# Speaker_Recommender
## Speaker Recommender System

Behind every excellent live performance is a quality public address (PA) system of amplifiers and loudspeakers.
Since these systems are costly to implement, it is crucial that sound engineers, production managers, and event planners choose their equipment well to ensure great sound quality at an optimal price. The speaker recommender system uses a buyer's
preferences to recommend new products, saving time and ensuring their money is well spent. 

## How it works (overview)

The recommender system holds a data frame of several different public address (PA) speaker products and their specifications. 
The user interacts with the system by providing/selecting a list of products which are liked and disliked based on prior experience. The recommender system then returns a ranked list of new similar products. 

In the background, the recommender system maps product specs to vectors in a high-dimensional feature space,
and compares these product vectors to a new vector constructed from user preferences. To compare vectors, the system uses Euclidean and cosine similarity measures. 

## Notebooks & Files

Check out the Speaker_Recommender.ipynb notebook to see how the recommender system works. 

The notebook includes:  

• Code used to scape Guitar Center's website for PA speaker product data.

• Data cleaning and exploratory analysis, including visualizations.

• Core algorithms which implement Euclidean and cosine comparissons.

• Preliminary validation analysis.

The cvs files contain data used by the recommender system to build useful data frames. 
