# SENTIMENT-ANALYSIS

*COMPANY*: CODETECH IT SOLUTIONS

*NAME*: MADHURI PANCHAKSHRI

*INTERN ID*: CT08JAI

*DOMAIN*: DATA ANALYSIS

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH


Twitter Sentiment Analysis Project
This project performs sentiment analysis on Twitter data using natural language processing (NLP) techniques and machine learning. It involves cleaning and preprocessing tweets, visualizing insights, and training a Logistic Regression model for sentiment classification.

Features
Data Cleaning:

Removes Twitter handles, special characters, numbers, and punctuations.
Stems words to their root forms for better analysis.
Data Visualization:

Generates word clouds to visualize frequent words for positive and negative sentiments.
Extracts and plots the top hashtags for both sentiments.
Feature Engineering:

Implements Bag-of-Words (BoW) using CountVectorizer for feature extraction.
Model Training:

Trains a Logistic Regression model on preprocessed tweets.
Evaluates performance using F1-score and accuracy metrics.
Customizable Threshold:

Adjusts the probability threshold for predictions to balance precision and recall.
Technologies Used
Languages: Python
Libraries:
Data Processing: pandas, numpy
Visualization: matplotlib, seaborn, wordcloud
NLP: nltk, re
Machine Learning: scikit-learn

How to Run
Clone the repository:
git clone https://github.com/MadhuriP2954/SENTIMENT-ANALYSIS
cd twitter-sentiment-analysis
Install the required libraries:
pip install -r requirements.txt
Add the dataset (Twitter Sentiments.csv) to the project directory.
Run the script:
python sentiment_analysis.py

Project Highlights
Practical Use Case: Demonstrates how to handle real-world text data from social media.
Interactive Visualizations: Provides insights into common words and hashtags for different sentiments.
Modular Code: Easy to extend with additional features or datasets.
