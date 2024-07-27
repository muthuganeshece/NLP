# NLP Projects Repository
**Hi👋🏾, Welcome to the NLP Projects Repository! This repository contains a collection of Natural Language Processing (NLP) projects developed to showcase various techniques and applications in the field.**

## Contents
- [**Basic Tweet Sentiment Classifier**](Practise/NLP1.ipynb)
- [**Medium Article Recommendation**](Practise/NLP2.ipynb)
- [**Basic Search Engine for Medium Article**](Practise/NLP3.ipynb)
- [**Email Auto fill system**](Practise/NLP4.ipynb)
- [**Topic Modelling**](Practise/NLP5.ipynb)

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

## NLP3 Notebook
### Basic Search Engine 
#### Libraries
- *NLTK, Gensim, TensorFlow, SciPy, SkLearn, Numpy, Pandas, re, Matplotlib*
#### Text Preprocessing
- *Stop word removal, punctuations etc.,*
- *Expanding the Text Contraction*  
#### Word Embedding - CBoW & Skipgram
- *Word Co-Occurence Matrix*
- *Multilabel Binary Encoding* ***(MLB)***
- *CBoW & Skipgram scratch implementation using tensorflow*
- ***CBoW*** *using Word2Vec*
- ***Skipgram*** *using Word2Vec*

## NLP4 Notebook
### Email Auto Fill  
#### Libraries
- *NLTK, WordCloud, Email, Numpy, Pandas, re, Matplotlib*
#### Text Preprocessing
- *New line, punctuations removal etc.,*
- *Expanding the Text Contraction*
- *Sentence Tokenization*
#### Probabilistic Language Models (PLM)
- ***Unigram*** *Model*
- ***Bigrams*** *Model*
- ***Trigrams*** *Model*
- *Model Evaluation using* ***Perplexity Score***
#### Outcomes
- ***Trigrams outperform Bigrams*** *in terms of perplexity score*
	- *Achieved* ***Mean Perplexity score of 3.03 for trigram model*** *whereas inf for bigram model*
- *Generative algorithm using trigram model for a 2 word seed. Though not synctactically correct, but the result is convincing*
![image](https://github.com/user-attachments/assets/c47a2a87-049d-4b86-a0bd-56013a9495ba)

## NLP5 Notebook
### Topic Modelling of Amazon Reviews  
#### Libraries
- *NLTK, Spacy, WordCloud, Numpy, Pandas, re, Seaborn*
#### Text Preprocessing
- *Expanding the Text Contraction*
- *Sentence Tokenization*
