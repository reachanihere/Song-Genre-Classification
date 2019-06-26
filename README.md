# Song-Genre-Classification
### Rock or rap?
 Classifying Song Genres from Audio Data. Applying Machine Learning methods in Python to classify songs into genres.

Using a dataset comprised of songs of two music genres (Hip-Hop and Rock), I trained a classifier to distinguish between the two genres based only on track information derived from [Echonest](http://the.echonest.com/)(now part of Spotify). Firstly, I used the ```pandas``` and ```seaborn``` packages in Python for subsetting the data, aggregating information, and creating plots when exploring the data for obvious trends or factors. Next, I used the ```scikit-learn``` package to predict whether I can correctly classify a song's genre based on features such as danceability, energy, acousticness, tempo, etc. I have gone over implementations of common algorithms such as PCA, logistic regression, decision trees, and so forth.
