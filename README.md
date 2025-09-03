# -Task-1_Sentiment-Analysis-on-IMDB-movie-Reviews
📌 Project Overview:

This project was developed as part of the Elevvo Pathways Internship – NLP Track.
The goal of this task is to build a Sentiment Analysis system that classifies IMDB movie reviews as positive or negative.
Sentiment analysis is a fundamental NLP task that helps in understanding the emotional tone behind text. By applying machine learning and NLP techniques, this project demonstrates how to process raw text, extract meaningful features, and train models to make predictions.

📂 Dataset
Source: IMDB Movie Reviews Dataset
Size: 50,000 reviews (25k training, 25k testing)
Labels:
1 → Positive review
0 → Negative review

🛠️ Steps Implemented:

Data Preprocessing
Text cleaning (removing stopwords, punctuation, lowercasing).
Tokenization and vectorization using TF-IDF.
Feature Extraction
Converted raw reviews into numerical feature vectors.
Model Training
Implemented and compared machine learning models such as:
Logistic Regression model
Naive Bayes
Evaluation
Accuracy, Precision, Recall, and F1-Score were computed.
Comparison of models to determine the best-performing classifier.


📊 Results:
The models were tested on unseen IMDB reviews.
Among the tested models, Logistic Regression model accuracy: 0.91325
Naive Bayes model (GaussianNB) accuraacy: 0.8329

🚀 Technologies Used:
Python 3
Jupyter Notebook
Libraries:
pandas
numpy
scikit-learn
nltk

Bonus tasks that has been done:

1- Visualized the most frequent positive and negative words

2- used a Naive Bayes classifier and compared accuracy


🚀To run the project check the requirements.txt file
