# book-recommendation-system
![image](https://user-images.githubusercontent.com/98402439/204297885-c4c98387-f31e-4947-9711-3ff27e693344.png)


## Problem Statement
During the last few decades, with the rise of Youtube, Amazon, Netflix, and many other such web services, recommender systems have taken more and more place in our lives. 

From e-commerce (suggest to buyers articles that could interest them) to online advertisement (suggest to users the right contents, matching their preferences), recommender systems are today unavoidable in our daily online journeys.

In a very general way, recommender systems are algorithms aimed at suggesting relevant items to users (items being movies to watch, text to read, products to buy, or anything else depending on industries).

Recommender systems are really critical in some industries as they can generate a huge amount of income when they are efficient or also be a way to stand out significantly from competitors. The main objective is to create a book recommendation system for users.

* EDA - Performed exploratory data analysis on numerical and categorical data.
* Data Cleaning - Missing value imputation,Outlier Treatment
* Feature Selection - Used User-ID,ISBN and Books-Rating for model development.
* Model development - Tried Popularity based model and Collaborative filtering.


## The Data
The Book-Crossing dataset comprises 3 files.

● Users :
Contains the users. Note that user IDs (User-ID) have been anonymized and map to integers. Demographic data is provided (Location, Age) if available. Otherwise, these fields contain NULL values.

● Books :
Books are identified by their respective ISBN. Invalid ISBNs have already been removed from the dataset. Moreover, some content-based information is given (Book-Title, Book-Author, Year-Of-Publication, Publisher), obtained from Amazon Web Services. Note that in the case of several authors, only the first is provided. URLs linking to cover images are also given, appearing in three different flavors (Image-URL-S, Image-URL-M, Image-URL-L), i.e., small, medium, large. These URLs point to the Amazon website.

● Ratings :
Contains the book rating information. Ratings (Book-Rating) are either explicit, expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit, expressed by 0.

## Dataset
https://drive.google.com/drive/folders/1ezD81dd7Ouy-j5hC3sag699MoE-zMVLq?usp=share_link

## Objective
The main objective is to create a book recommendation system for users. Recommender systems are really critical in some industries as they can generate a huge amount of income when they are efficient or also be a way to stand out significantly from competitors.
### Methods Used
* Descriptive Statistics
* Data Visualization
* Machine Learning

## Technolodgy
Popularity Based Filtering

Model Based Collaborative Filtering Recommender

Optimisation of SVD algorithm

Collaborative Filtering based Recommendation System

Implementing KNN

Popularity Based Recommender
It is a type of recommendation system which works on the principle of popularity and or anything which is in trend. These systems check about the books which are in trend or are most popular among the users and directly recommend them.

📖 Collaborative-based Filtering
Collaborative based filtering recommender systems are based on past interactions of users and target items. In simple words here, we try to search for the look-alike customers and offer products based on what his or her lookalike has chosen. Let us understand with an example. X and Y are two similar users and X user has watched A, B, and C movie. And Y user has watched B, C, and D movie then we will recommend A movie to Y user and D movie to X user.

## Conclusion
* In EDA, the Top-10 most rated books were essentially novels. Books like The Lovely Bone and The Secret Life of Bees were very well perceived.
* Majority of the readers were of the age bracket 20-35 and most of them came from North American and European countries namely USA, Canada, UK, Germany and Spain.
* If we look at the ratings distribution, most of the books have high ratings with maximum books being rated 8. Ratings below 5 are few in number.
* Author with the most books was Agatha Christie, William Shakespeare and Stephen King.
* For modelling, it was observed that for model based collaborative filtering SVD technique worked way better than NMF with lower Mean Absolute Error (MAE) .
* Amongst the memory based approach, item-item CF performed better than user-user CF because of lower computation .

## References
Shivam Baldha, 'Introduction to Collaborative Filtering'. [Online].

Available: https://www.analyticsvidhya.com/blog/2022/02/introduction-to-collaborative-filtering/

Alexandre Wrg, 'An overview of several recommendation systems'. [Online].

Available: https://towardsdatascience.com/an-overview-of-several-recommendation-systems-f9f8afbf00ea/

Youtube.com, 'Book Recommender System'. [Online].

Available: https://www.youtube.com/watch?v=1YoD0fg3_EM&t=1s/
