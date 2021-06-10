# Arun-Travel-Reviews-Analysis
Development of an Aspect Based Sentiment Model for Travel Reviews in Arun District.

Notebooks are numbered to indicate sequence. All datasets are contained in the separate Datasets folder and each notebook indicates which datasets are needed to run the notebook and the files where processed data is saved to for use in another notebook.

* Exploratory Data Analysis - Notebook 1 and Notebook 2
* Base Sentiment Models:
*  - Notebook 3 Review Post Attributes Models (user location, past contributions etc to predict binary user score)
*  - Notebook 4 Review Text Attributes Models (number of words, use of punctuation, capitalisation etc to predict binary user score)
*  - Notebook 5 Text Preprocessing (text cleaning process - tokenization, spelling, lemmatization, regex etc)
*  - Notebook 6 Unsupervised Models (Textblob and Vader on uncleaned and cleaned text to predict binary user score)
*  - Notebook 7 Review Text Content Models (cleaned text models to predict sentiment based on binary user score)
*  - Notebook 8 Review Text Content Neural Network Models (minimally cleaned text to predict sentiment on binary user score) NOTE MAKE SURE KERAS AND TENSORFLOW LOADED
* Aspect Extraction:
* - Keyword and Noun Phrase Extraction (cleaned reviews)
* - LDA and NMF Topic Models using Nouns (cleaned reviews, exploded to sentence and then to noun phrases and noun words extracted)
* - Visualisation of Aspects from NMF topic modelling
             
