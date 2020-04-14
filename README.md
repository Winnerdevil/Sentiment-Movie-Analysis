# Sentiment-Movie-Analysis

Sentiment Analysis is the process of computationally identifying and categorizing opinions expressed in a piece of text, especially in order to determine whether the writer's attitude towards a particular topic, product, etc. is positive, negative, or neutral.

Sentiment Analysis is also referred as Opinion Mining. It’s mostly used in social media and customer reviews data.

In this Machine learning project on Sentiment Movie Analysis it's based on the supervised Learning. Supervised learning is the Data mining task of inferring a function from labeled training data. The training data consist of a set of training examples. In supervised learning, each example is a pair consisting of an input object (typically a vector) and a desired output value (also called the supervisory signal).

 # Training Set
We have use the NLTK’s movie_reviews corpus as our labeled training data. The movie_reviews corpus contains 2K movie reviews with sentiment polarity classification. It’s compiled by Pang, Lee.

Here, we have two categories for classification. They are: positive and negative. The movie_reviews corpus already has the reviews categorized as positive and negative.

# Feature Extraction
To classify the text into any category, we need to define some criteria. On the basis of those criteria, our classifier will learn that a particular kind of text falls in a particular category. This kind of criteria is known as feature. We can define one or more feature to train our classifier.

So, in this project ***Bag of words*** feature is used.

### Bag of words feature shown below:
<ul>
<li>We will use all the useful words of each review while creating the feature set.</li>
<li>We take a fixed number of positive and negative reviews for train and test set.</li>
<li>This results in equal distribution of positive and negative reviews across train and test set.</li>
</ul>

more about ***Bag of words*** can be get from: 
https://en.wikipedia.org/wiki/Bag-of-words_model


