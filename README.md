# Netflix-Movies-And-TV-Shows-Clustering
Clustered similar contents by matching text-based features

# Project Summary

Netflix is a popular streaming service that provides its subscribers with a wide range of movies, TV shows, documentaries, and original content to watch on demand. The company was founded in 1997 as a DVD rental service but later pivoted to an online streaming model in 2007. Since then, Netflix has grown into one of the most popular streaming services globally, with over 200 million subscribers in more than 190 countries as of 2021.

Netflix's success is due in part to its innovative business model and emphasis on creating original content. The company invests heavily in producing its own movies and TV shows, which have won numerous awards and attracted high-profile talent. Netflix also uses sophisticated algorithms to recommend content to its users, based on their viewing history and preferences.

This project aimed to identify patterns in the content available on the platform and group them into clusters based on similarities in their genres, sub-genres, release year, and other features. The project utilized machine learning algorithms such as K-means clustering and Hierarchical Clustering to cluster the data.

# Problem Statement

This dataset contains tv shows and movies available on Netflix as of 2019. The data is collected from Flixable which is a third-party Netflix search engine. In 2018, they released an interesting report which shows that the number of tv shows on Netflix has nearly tripled since 2010. The streaming service's number of movies has decreased by more than 2000 titles since 2010, while its number of tv shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

### In this project, i did
* Exploratory Data Analysis
* Understood what types of content are available in different countries.
* If Netflix has been increasingly focusing on TV rather than movies in recent years.
* Clustered similar content by matching text-based features.

# Conclusion

Majority of the content on Netflix is movies, but in recent years it has been focusing more on Tv-Shows.
Most of the contents are for adults, while very few contents are for teens and kids. On the other side, most of the contents are added in the month of December and January. If I talk about the day, then a majority of the contents are added on the first day of the month followed by the first day of the third week of the month.

Majority of the features have textual value so I applied NLP to that for preprocessing the data. After that, the dimension increased to 10000. So I applied PCA for dimensionality reduction, and I ended up with 4000 features.

I implemented two models kmeans and agglomerative clustering. In kmeans I got 6 cluster value with the elbow method and silhouette score. So finally I chose 6 number of clusters as my optimal k value. At last through dendrogram i found the optimal value for k is 4. So i ended up doing agglomerative clustering with four clusters.
