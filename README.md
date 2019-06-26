# Song-Genre-Classification
### Rock or rap?
 Classifying Song Genres from Audio Data. Applying Machine Learning methods in Python to classify songs into genres.

Using a dataset comprised of songs of two music genres (Hip-Hop and Rock), I trained a classifier to distinguish between the two genres based only on track information derived from [Echonest](http://the.echonest.com/)(now part of Spotify). Firstly, I used the ```pandas``` and ```seaborn``` packages in Python for subsetting the data, aggregating information, and creating plots when exploring the data for obvious trends or factors. Next, I used the ```scikit-learn``` package to predict whether I can correctly classify a song's genre based on features such as danceability, energy, acousticness, tempo, etc. I have gone over implementations of common algorithms such as PCA, logistic regression, decision trees, and so forth.

Tasks:
1. Preparing our dataset
2. Pairwise relationships between continuous variables
3. Normalizing the feature data
4. Principal Component Analysis on our scaled data
5. Further visualization of PCA
6. Train a decision tree to classify genre
7. Compare our decision tree to a logistic regression
8. Balance our data for greater performance
9. Does balancing our dataset improve model bias?
10. Using cross-validation to evaluate our models
