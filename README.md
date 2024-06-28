# NLP Projects Repository
**Hi👋🏾, Welcome to the NLP Projects Repository! This repository contains a collection of Natural Language Processing (NLP) projects developed to showcase various techniques and applications in the field.**

## Contents
- [**Tweet Sentiment Classifier**](Practise/NLP1.ipynb)
- [**Medium Article Recommendation**](Practise/NLP2.ipynb)

## NLP1 Notebook 
### Tweet Sentiment Classifier (Binary Classification)
- #### Libraries
	- *NLTK, Sklearn, Pandas, Numpy, regex*
- #### Data Exploration
	- ***Univariate Analysis*** *of each column (UVA)*
 	- *Data distribution study*	
- #### Text Preprocessing:
	- *Stop word removal, hyperlink removal, punctuations etc.,*
	- ***Stemming***
 	- *Tweet* ***Tokenization***
- #### Text to Numerical Vector:
	- ***Sparse representation*** of text as a vector
	- *[**Bias, posfreq, negfreq**], 3 dimensional vector generation for each unique word in the dataset* 
- #### Model:
	- *Prepared a simple* ***Logistic Regression*** *classification model*
	- *Training Accuracy:* ***0.62***
	- *Testing Accuracy:* ***0.57***

## NLP2 Notebook
### Medium Article Recommendation System
#### Libraries
- *NLTK, Contractions, Sklearn, Pandas, Numpy, re, matplotlib*
#### Text Preprocessing:
- *Stop word removal, punctuations etc.,*
- *Expanding the Text Contraction*
- Word ***Lemmatization***
- Word ***Tokenization***	
#### Bag of Words (BoW)
- *Implementation without library*
- *Implementation with* ***CountVectorizer***
- ***PCA*** *for dimensionality reduction and visualize the patterns*
- ***Cosine Similarity*** *measured between articles*
- ***Top 10 recommendations*** *for randomly selected article*

#### Term Frequency Inverse Document Frequency (TF-IDF)
- *Implementation without library*
- *Implementation with* ***TFIDFVectorizer***
- ***PCA*** *for dimensionality reduction and visualize the patterns*
- ***Cosine Similarity*** *measured between articles*
- ***Top 10 recommendations*** *for randomly selected article*
