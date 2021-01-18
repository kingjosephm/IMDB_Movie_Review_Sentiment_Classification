## IMDB Movie Review Sentiment Classification

In this project, I apply a few well-known natural language 
processing (NLP) methods to a binary sentiment classification problem using
[Kaggle's IMDB Movie Review dataset](https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews).
This dataset comprises 25,000 positive and 25,000 negative movie reviews. For
comparison sake, I use both unsupervised (i.e. VADER, TextBlob) and supervised
(i.e. naive Bayes, Word2Vec, GloVe) learning algorithms. At the time of this writing,
this dataset was no longer part of an active Kaggle competition; as a result, there
is no actual unlabeled test set. Instead, I divide the provided (labeled) dataset
into train and test sets, using unseen latter set to evaluate each model's
performance.