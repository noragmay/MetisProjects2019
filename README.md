## Metis Data Science Portfolio - Project McNulty (03)

For this project, I set out to build a classification model for TV shows to predict if they will have a "next season." 

The data came from IMDb. I used the information about 150,000 TV series (genre, start date, current season number, imdb score and votes per episode). 

The data set was balanced between "yes" renewed and "no" not renewed. I separated the test/train/validation sets keeping entire shows together, however each observation was information about single season of a show and whether or not it was renewed.

With a random forest model with 100 trees with max depth of 11, I was able to achieve 72% accuracy on the test set.
