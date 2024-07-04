# capstone-project-netflix-clustering-machine-learning-project

# Capstone-Project-Netflix-Movies-and-TV-Shows-Clustering-machine-learning
Netflix Inc. is an American media corporation headquartered in Los Gatos, California. Reed Hastings and Marc Randolph founded the company in Scotts Valley, California, in 1997. It operates the over-the-top subscription video on-demand service Netflix, which includes original films and television series commissioned or acquired by the company, as well as third-party content licenced from other distributors.

This dataset contains television series and films available on Netflix. The dataset is sourced from Flexible, a third-party Netflix search engine. Netflix movie and TV programme clustering is a data analysis and machine learning technique that divides its material into related groups.This technique entails analysing each title's numerous properties, such as genre, cast, and plot, and then applying algorithms to uncover patterns and commonalities. In essence, it is a collection of algorithms that employ machine learning to analyse user data and movie evaluations. To make it more efficient, Netflix has created 1,300 recommendation clusters based on users' viewing habits. Netflix's target demographic consists of youthful, tech-savvy consumers as well as everyone with digital connectivity. Netflix's fanbase is diverse in age and demographics. However, the majority of the audience consists of youngsters, college students, entrepreneurs, and working professionals. Netflix's target audience is segmented based on demographics, behavioural intentions, and psychographic characteristics.The arrangement, like most licencing deals, is structured in a typical manner, with Netflix paying for each picture using rate cards based on each title's domestic or international box office receipts. Netflix use machine intelligence and algorithms to help viewers overcome preconceived preconceptions and discover shows they might not have picked otherwise. To accomplish this, it looks for intricate threads within the text rather than broad genres to make predictions.

Generally, movie recommendation algorithms divide users into a finite number of comparable categories based on their previous actions and profiles. Then, on a fundamental level, folks in the same cluster receive identical recommendations. Netflix created a new machine learning algorithm based on reinforcement learning to generate an optimal list of recommendations given the user's limited time budget. Here are seven instances of clustering methods in use.

Identifying Fake News. Fake news is not a new phenomenon, but it is one that is becoming prolific.

Spam filter.

Marketing and Sales.

Classifying network traffic.

Identifying fraudulent or criminal activity.

Document analysis.

Fantasy Football and Sports.

This dataset includes TV episodes and films accessible on Netflix as of 2019. The dataset is sourced from Flixable, a third-party Netflix search engine.

In 2018, they published an interesting research revealing that the quantity of TV series on Netflix has nearly tripled since 2010. Since 2010, the number of films available on the streaming service has declined by almost 2,000, but the number of TV episodes has nearly tripled. It will be interesting to see what additional insights can be extracted from the same dataset.

Integrating this dataset with additional external datasets, such as IMDB ratings and rotten tomatoes, can yield numerous intriguing results.

About the Data :

We have the data of which contains details of customers like id , age, gender and also contains the details of the customers vehicle

Dataset info:


Number of records: 7787

Number of features: 12

Features information:

The dataset contains features like:


show_id : Unique ID for every Movie / Tv Show

type : A Movie or TV Show

title : Title of the Movie / Tv Shows

director : Director of the Movie

cast : Actors involved in the movie / show

country : Country where the movie / show was produced

date_added : Date it was added on Netflix

release_year : Actual Release year of the movie / show

rating : TV Rating of the movie / show

duration : Total Duration - in minutes or number of seasons

listed_in : Generes

description: The Summary description

Project Work flow:

- Importing Libraries,
- Loading the dataset,
- Data Summary,
- Data Cleaning & Data Analysis,
- Feature selection,
- Implementing different clustering methods,
- Conclusion,
- Future Work.




![image](https://github.com/samchak18/Capstone-Project-4_Netflix-Movies-and-TV-Shows-Clustering/assets/114379464/8eb63ae3-09a2-40a5-93eb-f692c933e181)




Conclusion:

- Director and cast contains a large number of null values so we will drop these 2 columns .
- In this data-set there are two types of contents where 30.86% includes TV shows and the remaining 69.14%  carries Movies.
- We have reached a conclusion from our analysis from the content added over years that Netflix is focusing
movies and TV shows (From 2016 data we get to know that Movies is increased by 80% and TV shows is  increased by 73% compare)
- From the data-set insights we can conclude that the most number of TV Shows released in 2017 and for  Movies it is 2020
- On Netflix USA has the largest number of contents. And most of the countries preferred to produce movies  more than TV shows.
- Most of the movies are belonging to 3 categories
- TOP 3 content categories are International movies , dramas , comedies.
- 	In text analysis (NLP) I used stop words, removed punctuation's , stemming & TF-IDF vectorizer and other  functions of NLP.
- 	Applied different clustering models like K-means, hierarchical, Agglomerative clustering, DBSCAN on data we got the best cluster arrangements.
- 	By applying different clustering algorithms to our data-set .we get the optimal number of  cluster is equal to 3
- 	From this clustering analysis we can create Netflix movies and tv shows recommendation systems & also we can use topic modelling.
