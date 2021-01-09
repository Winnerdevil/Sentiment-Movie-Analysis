# Sentiment-Movie-Analysis

Sentiment Analysis is the process of computationally identifying and categorizing opinions expressed in a piece of text, especially in order to determine whether the writer's attitude towards a particular topic, product, etc. is positive, negative, or neutral.

Sentiment Analysis is also referred as Opinion Mining. It’s mostly used in social media and customer reviews data.

 # This Project
 In this project on ***Sentiment-Movie-Analysis*** I have trained the model using nltk's movie_reviews training set and then try to predict the nature of the reviews given to a movie.
 
 # Training Set
I have use the NLTK’s movie_reviews corpus as our training data. The movie_reviews corpus contains 2000 movie reviews with it's classification(1000 'pos' data and 1000 'neg' data). It is been given by Pang, Lee.

In the movie_reviews corpus they have already classifies the two category named positive and negative.

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

more about ***Bag of words*** can be get from: <br>
https://www.freecodecamp.org/news/an-introduction-to-bag-of-words-and-how-to-code-it-in-python-for-nlp-282e87a9da04/

https://en.wikipedia.org/wiki/Bag-of-words_model


