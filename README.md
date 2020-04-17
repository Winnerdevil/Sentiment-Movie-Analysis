# Sentiment-Movie-Analysis

Sentiment Analysis is the process of computationally identifying and categorizing opinions expressed in a piece of text, especially in order to determine whether the writer's attitude towards a particular topic, product, etc. is positive, negative, or neutral.

Sentiment Analysis is also referred as Opinion Mining. It’s mostly used in social media and customer reviews data.

In this Machine learning project on Sentiment Movie Analysis it's based on the supervised Learning. Supervised learning is the Data mining task of inferring a function from labeled training data. The training data consist of a set of training examples. In supervised learning, each example is a pair consisting of an input object (typically a vector) and a desired output value (also called the supervisory signal).

 # This Project
 In this project on ***Sentiment-Movie-Analysis*** we have trained the model using nltk's movie_reviews training set and then try to predict the nature of the reviews given to a movie.
 
 We have also printed the probabililty of getting a negative reviews and positive reviews at last.
 # Training Set
We have use the NLTK’s movie_reviews corpus as our training data. The movie_reviews corpus contains 2K movie reviews with it's classification. It is been given by Pang, Lee.

In the movie_reviews corpus they have already classifies the two category named positive and negative. So it is easy to work on this data.

# Feature Extraction
Feature Extraction is the process of learning, the model/classifier to classify the particular text into its category(here, positive and negative). And there can be many features to train the model/classifier.

So, in this project ***Bag of words*** feature is used.

### Bag of words feature shown below:
Bag of Words (BOW) is a method to extract features from text documents. These features can be used for training machine learning algorithms. It creates a vocabulary of all the unique words occurring in all the documents in the training set.

In simple terms, it’s a collection of words to represent a sentence with word count and mostly disregarding the order in which they appear.

BOW is an approach widely used with:
<ol>
<li>Natural language processing</li>
<li>Information retrieval from documents</li>
<li>Document classifications</li>
</ol>

we have refer this on:  
https://www.freecodecamp.org/news/an-introduction-to-bag-of-words-and-how-to-code-it-in-python-for-nlp-282e87a9da04/

more about ***Bag of words*** can be get from: 
https://en.wikipedia.org/wiki/Bag-of-words_model


