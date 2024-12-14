# Movie-Review-Sentiment-Classification-Dutch-

This project focuses on building a sentiment classification model for Dutch language movie reviews. The solution classifies movie reviews as either Positive, Average, or Negative. It processes the provided CSV file of reviews and uses several preprocessing steps, including language detection, tokenization, sentiment handling, and chunking to process long reviews.

Problem Description
The dataset consists of movie reviews in Dutch, and the task is to classify these reviews into three categories:

Positive
Average
Negative
This project uses a series of Python libraries and techniques such as language detection, text preprocessing, sentiment analysis, and chunking to handle long text inputs effectively.

Features
Language Detection: Reviews are filtered to retain only Dutch-language reviews.
Text Preprocessing: Reviews are tokenized, lemmatized, and cleaned, removing stop words and handling emojis and negations.
Sentiment Analysis: Reviews are classified into one of three sentiment categories (Positive, Negative, Neutral) using a zero-shot classification pipeline.
Data Visualization: The project includes data exploration through bar charts and pie charts, visualizing review lengths and sentiment distribution.
