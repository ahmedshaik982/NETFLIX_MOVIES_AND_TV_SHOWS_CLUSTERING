# Netflix_Movies_And_Tv_Shows_Clustering
This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.
In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.
Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

## Dataset
Download the dataset for this project from following Link
https://github.com/ahmedshaik982/NETFLIX_MOVIES_AND_TV_SHOWS_CLUSTERING/blob/main/NETFLIX%20MOVIES%20AND%20TV%20SHOWS%20CLUSTERING.csv

## Data Information
The dataset has 7787 rows and 12 columns

* show_id : Unique ID for every Movie / Tv Show

* type : Identifier - A Movie or TV Show

* title : Title of the Movie / Tv Show

* director : Director of the Movie

* cast : Actors involved in the movie / show

* country : Country where the movie / show was produced

* date_added : Date it was added on Netflix

* release_year : Actual Releaseyear of the movie / show

* rating : TV Rating of the movie / show

* duration : Total Duration - in minutes or number of seasons

* listed_in : Genere

* description: The Summary description

## Work Flow
![image](https://user-images.githubusercontent.com/117965293/209428187-c3c4c916-63c6-4a44-9a99-d4f90e1a6464.png)

## Tools used
* Google colab notebook
* Pandas library
* Numpy
* Matplotlib and Seaborn for data visualization
* Scikit Learn for implementing Machine Learning Models.

## Some Visualizations
![image](https://user-images.githubusercontent.com/117965293/209429879-8a30ab12-de13-4d94-8ead-97a913f047f7.png)


## Conclusions
* There are more movies that tv shows on netflix

* Jan Suter and Raul Campos directed most number of movies.

* Alastair Fothergill and Ken Burns directed most number of TV Shows.

* Anupam Kher acted in most number of movies followed by Shah Rukh Khan.

* Takahiro Sakurai acted in most number of TV Shows followed by Junichi Suwabe

* United States produced most number of movies/Tv Shows followed by India.

* Most number of movies are released in the month of december and january.

* In the year 2018 most number of movies and TV Shows are released.

* In the recent years, netflix has started to increase the TV Shows content.

* Most number of movies and TV SHows belongs the rating category of 'TV-MA'

* Most number of movies / TV Shows are from genre of 'International Movies' followed by dramas.

* Most number of movie duration is in the range of 80 to 125 min.

* Most number of TV Shows have only One season.

* Most number of movies and TV Shows are made for adults only.

* The content for Adults is mostly made from Spain and France countries.

* The content for Teens is mostly made from Egypt and India countries.

* The content for Older Kids is mostly made from Japan country.

* The content for Kids is mostly made from Canada country.

* The content for Adults is mostly released in recent years(2020, 2019, 2018, 2017).

* The content for Teens is mostly released in the year 2010 and 2012.

* The content for Older is Kids released in year of 2014.

* The content for Kids is mostly released in the year of 2020.

* The content for Adults is mostly from the genre of 'stand up comedy' followed by Dramas.

* The content for Teens is mostly from the genre of 'Comedies,Dramas, international movies'

* The content for Older Kids is mostly from the genre of 'Children, Family movies and Comedies'

* The content for Kids is mostly from the genre of Kids TV and Children and Family Movies

* 94% content from Raul Campos and Jan Suter is for adults.

* Steven Spielberg , David Dhawan and Cathy Garcia-Molina are the directors who makes content mostly for Teens and Older Kids.

* By using the data, a recommender system was created with cosine similarity.

* By using the data, created a clusters using kmeans and hierarchical clustering.

* By applying silhouette analysis, for k means, the optimal k value is 6.

* And for k = 6, silhouette score is 0.5001759759427156

* For heirarchical clustering, from dendrogram we can choose optimal k value as 3. And silhouette score is 0.5049348034764315
