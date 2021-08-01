# Arun-Travel-Reviews-Analysis
Development of an Aspect Based Sentiment Model for Travel Reviews in Arun District.

Notebooks are numbered to indicate sequence. Datasets are contained in the separate Datasets folder and each notebook indicates which datasets are needed to run the notebook and the files where processed data is saved to for use in another notebook. 

Notebooks where other models or methods have been explored to try and find other ways to address the problem but not expected to be part of the final write-up are included in the 'Other Notebooks' section. 

* Exploratory Data Analysis - Notebook 1 and Notebook 2
* Base Sentiment Models:
*  - Notebook 3 Review Post Attributes Models (user location, past contributions etc to predict binary user score)
*  - Notebook 4 Review Text Attributes Models (number of words, use of punctuation, capitalisation etc to predict binary user score)
*  - Notebook 5 Text Preprocessing (text cleaning process - tokenization, spelling, lemmatization, regex etc)
*  - Notebook 6 Unsupervised Models (Textblob and Vader on uncleaned and cleaned text to predict binary user score)
*  - Notebook 7 Review Text Content Models (cleaned text models to predict sentiment based on binary user score)
*  - Notebook 8 Review Text Content Neural Network Models (cleaned text to predict sentiment on binary user score)
 
* Topic Models:
* - Notebook 9 Keyword and Noun Phrase Extraction (cleaned reviews)
* - Notebook 10 LDA and NMF Topic Models using Nouns (cleaned reviews, exploded to sentence and then to noun phrases and noun words extracted)
* - Notebook 11 Visualisation of Aspects from topic modelling output - including comparison of aspects across towns per category

* Aspect and Sentiment Models
* - Notebook 12a Aspect Models using nouns and machine learning models
* - Notebook 12b Aspect Models using nouns and neural network models 
* - Notebook 13a Binary Sentiment Models using noun phrases and machine learning models 
* - Notebook 13b Binary Sentiment Models using noun phrases and neural network models
* - Notebook 13c Multiclass Sentiment Models using noun phrases and machine learning models
* - Notebook 13b Multiclass Sentiment Models using noun phrases and neural network models
* - Notebook 14a Combined Aspect and Sentiment Model Using Binary Sentiment
* - Notebook 14b Combined Aspect and Sentiment Model Using Multiclass Sentiment

* Opinion Spam
* - Notebook 15 Opinion Spam Review
  
* Other Notebooks (Other Methodologies Investigated as part of the Review but not deemed to be useful or successful)
* - KMeans Clustering (TFIDF vectors used as input to KMeans clustering)
* - Word2Vec and Doc2Vec vectors (as input to ML models)
* - SemEval restaurant dataset (investigating whether a model can be trained to label the Arun food data)
* - Aspect extraction with Spacy and language rules
