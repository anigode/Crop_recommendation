1.	Amazon Product Review Sentiment Analysis
This project implements sentiment analysis on Amazon product reviews using Natural Language Processing (NLP) techniques. The analysis involves pre-processing the text data, applying various machine learning models, and evaluating their performance.

2.	Table of Contents
•	[Introduction](#introduction)
•	[Installation](#installation)
•	[Usage](#usage)
•	[Data](#data)
•	[Models](#models)
•	[Evaluation](#evaluation)
•	[Libraries](#libraries)
•	[License](#license)

3.	Introduction
The aim of this project is to predict product ratings based on user reviews. It uses techniques such as stemming, lemmatization, and TF-IDF vectorization to process the text data. The project employs multiple classification models, including Random Forest, Decision Tree, Support Vector Machine, and Logistic Regression.

4.	Installation
To set up the project, clone the repository and install the required libraries. Ensure you have Python installed (preferably version 3.6 or above).

5.	Usage
•	Place your dataset CSV file (e.g., 1429_1.csv) in the project directory.
•	Run the sentiment_analysis.py script to execute the analysis.
•	The cleaned data will be saved as amazon_data.csv in the project directory.

6.	Data
•	The project uses a dataset containing Amazon product reviews, which includes:
•	reviews.userCity: City of the user
•	reviews.userProvince: Province of the user
•	reviews.id: Unique identifier for each review
•	reviews.rating: Rating given by the user (target variable)
•	reviews.text: Text of the user review
•	The script removes unnecessary columns and deals with missing values in the dataset.

7.	Models
	The following machine learning models are implemented in this project:
•	Random Forest Classifier
•	Decision Tree Classifier
•	Support Vector Machine
•	Logistic Regression
	Each model is evaluated using accuracy scores and classification reports.

8.	Evaluation
The performance of each model is evaluated based on accuracy and various classification metrics (precision, recall, F1-score). The results for different n-grams (unigrams, bigrams, trigrams, and n-grams) are also compared.

9.	Libraries
	The project depends on the following Python libraries:
•	pandas
•	matplotlib
•	numpy
•	seaborn
•	nltk
•	sklearn
