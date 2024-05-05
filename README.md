This repository contains the code and resources used to analyze tweets and classify their sentiment towards two tech brands: Samsung and Apple. The project aims to explore public opinion on social media using machine learning techniques.

**Objective:**

Develop a machine learning model to classify tweet sentiment (positive or negative)
Analyze sentiment towards Samsung and Apple brands in a collection of tweets
Compare public perception between the two brands

**Methodology:**

**Data Acquisition:**
Utilize a labeled dataset of 1.6 million tweets from Kaggle (likely containing positive/negative sentiment annotations)
Collect 3.5 million new tweets mentioning "Samsung" and "Apple" using the Twitter API (Tweepy)

**Data Preprocessing:**
Implement standard NLP techniques for data cleaning:
Remove punctuation, URLs, and mentions
Eliminate stopwords
Substitute emoticons with textual equivalents

**Feature Engineering:**
Employ TF-IDF (Term Frequency-Inverse Document Frequency) to assign weights to words based on their significance within individual tweets and overall dataset rarity.

**Model Training:**
Train three machine learning models for sentiment classification:
1. Logistic Regression
2. Support Vector Machine (SVM)
3. Bernoulli Naive Bayes

**Model Evaluation:**
Evaluate model performance using metrics like accuracy, precision, recall, and F1-score. Select the best-performing model based on these metrics.

**Sentiment Analysis on New Data:**
Utilize the trained model to classify sentiment in the newly collected tweets mentioning "Samsung" and "Apple".
Analyze the results to compare public sentiment between the two brands.
