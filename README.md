# NETFLIX-MOVIES-TV-SHOWS-CLUSTERING-
Netflix is a company that manages a large collection of TV shows and movies, streaming it anytime via online. This business is profitable because users make a monthly payment to access the platform. However, customers can cancel their subscriptions at any time. 
Therefore, the company must keep the users hooked on the platform and not lose their interest. This is where recommendation systems start to play an important role, providing valuable suggestions to users is essential.

Netflix Recommender recommends Netflix movies and TV shows based on a user's favourite movie or TV show. It uses a Natural Language Processing (NLP) model and a K-Means Clustering model to make these recommendations. These models use information about movies and TV shows such as their plot descriptions and genres to make suggestions. The motivation behind this project is to develop a deeper understanding of recommender systems and create a model that can perform Clustering on comparable material by matching text-based attributes. Specifically, thinking about how Netflix create algorithms to tailor content based on user interests and behavior.

•	The project's main goal is to create a model that can perform Clustering on comparable material by
matching text-based attributes.
•	As the problem statement says, understanding what type of content is available in different countries
and Is Netflix increasingly focused on TV rather than movies in recent years we have to do clustering
on similar content by matching text-based features. For that we used Affinity Propagation, Agglomerative Clustering, and K-means Clustering.

CONCLUSION 

	Data set contains 7787 rows and 12 columns in that cast and director features contains large number of missing values so we can drop it and we have 10 features for the further implementation.
	 We have two types of content TV shows and Movies (30.86% contains TV shows and 69.14%contains Movies).
	The most number of the movies and TV shows release in 2017 and 2020 respectively and united nation have the maximum content on Netflix 
	On Netflix, Dramas genre contains the maximum content among all of the genres and the most of the content added in December month and less content in February.
	By applying the silhouette score method for n range clusters on dataset we got best score which is 0.244for 4 clusters it means content explained well on their own clusters, by using elbow method after k =4 curve gets linear it means k =4 will be the best cluster 
	By applying different clustering algorithms to our dataset, we get the optimal number of cluster is equal to 4.
	We have done null value treatment, feature engineering, and EDA since loading the dataset then completed assigned tasks. 
	Among different types of content available in different countries, content TV-MA is available in most countries. This could be because it shows that it is just for adult audiences, and the Netflix audience enjoys content like this. 
	We have also explained different clusters based on their content; Defined clusters and enforced the K-means clustering algorithm and cluster number nine has the most clusters; we have also plotted a scatter plot in which we may interact with similar content about that cluster.
