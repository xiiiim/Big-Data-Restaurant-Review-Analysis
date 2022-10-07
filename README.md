# Restaurant-Review-Analysis

Yelp has collected enormous amount of data comprising of user’s reviews and rating for businesses over many years.
Online reviews play a very important role in information dissemination and are influencing user decision. However, a user may only read star ratings before coming to a decision. 

Our aim for this project is to predict the positive and negative ratings for a business based on the text-reviews. We are focusing on ‘Restaurant’ reviews, as they constitute more than 60% of the total reviews.

Our approach:
In this project, we collected and used Hadoop to store the Yelp Reviews dataset in HDFS- Hadoop Distributed FileSystem. After cleaning and conducting feature engineering using Pyspark, We tested serveral NLP techniques(Word2VecModel, tf-idf, and hashing) to map terms to features to predict ratings from restaurant reviews using Logistic Regression and Multinomial Naive Bayes models.
