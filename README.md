# Sentiment Classification for Dutch Movie Reviews

This project focuses on building a sentiment classification model specifically designed for Dutch-language movie reviews. The goal is to classify movie reviews into three categories: Positive, Neutral, or Negative. The model processes the provided CSV file of reviews by applying a variety of preprocessing steps, such as language detection, tokenization, sentiment handling, and chunking, to manage long reviews effectively.

## Problem Description

The dataset consists of movie reviews in Dutch, and the task is to classify these reviews into three sentiment categories:
- **Positive**
- **Neutral**
- **Negative**

The solution leverages several Python libraries and techniques to handle the reviews efficiently, including language detection, text preprocessing, sentiment analysis, and chunking to address long text inputs.

## Features

- **Language Detection**: The reviews are filtered to retain only Dutch-language reviews, ensuring the model processes relevant data.
  
- **Text Preprocessing**: Reviews undergo tokenization, lemmatization, and cleaning. This step removes stop words, handles emojis, and manages negations to improve the accuracy of sentiment analysis.
  
- **Sentiment Analysis**: Using K-means and zero-shot classification pipeline (using **GroNLP/bert-base-dutch-cased**, a pre-trained language model based on BERT, specifically fine-tuned for the Dutch language), the reviews are classified into one of three sentiment categories: **Positive**, **Negative**, or **Neutral**.
  
- **Data Visualization**: The project includes visualizations such as bar charts and pie charts, which display insights on review lengths and sentiment distribution, offering a clear understanding of the dataset.

## Note
The dataset for this project, called **ReviewsTestSet_1.csv**, is provided in the data folder. If you're running the project locally, you'll need to download the dataset and update the file path in the script accordingly.

## Installation

To get started with this project, ensure you have Python 3.6+ installed. Then, install the necessary dependencies by running the following command:

```bash
pip install -r requirements.txt
