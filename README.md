# TED-Talks-Topic-modeling-and-classification

![alt tag](img.png)

## Goal:

#### Topic Modeling 

#### Classify documents into their categories

#### Information retrieval using DOC2VEC

## Data Descreption:

Web scraped TED talk transcripts Category wise

835 TED talks 

5 Categories: 

business = 123
entertainment = 152
global issues = 245
science = 209
technology = 249

## Pre-process:

#### encoding

#### Stop words removal and punctuations

#### Lemmatization

#### POS tagging and retaining “NN” and “NNP” -  helps Topic Modeling

## EDA

## Topic Modeling:
TFIDF/count vectorize 

NMF better than LDA

pyLDAvis

Around 40% accuracy after manually labelling the topics and assigning the document to the topic with maximum weight 

# Base line performance : 30%

# Accuracy on TFIDF :

### SVM = 72%

### Random forest = 63%

### knn = 64%

### gradient boosting = 54%

### LDA =  49 %

# Accuracy on Doc2Vec document vectors :

### Random Forest = 57%

### Knn = 56.6%










