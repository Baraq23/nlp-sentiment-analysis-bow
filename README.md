# Natural Language Processing (NLP) Learning Project

This repository contains practical exercises for learning Natural Language Processing fundamentals using Python.

## Project Overview

This project demonstrates core NLP concepts including text preprocessing, tokenization, stemming, and bag-of-words vectorization using real Twitter data for sentiment analysis.

## Files Description

- **preprocessing.ipynb** - Text preprocessing exercises covering lowercase conversion, punctuation removal, tokenization, stop word removal, and stemming
- **bag_of_words.ipynb** - Implementation of bag-of-words model using sklearn's CountVectorizer
- **tweets_train.txt** - Training dataset containing labeled tweets (positive, negative, neutral)
- **requirements.txt** - Python dependencies

## Prerequisites

- Python 3.x
- Jupyter Notebook

## Installation

1. Clone this repository
2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Download NLTK data (run once):
   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('stopwords')
   ```

## Usage

1. Start with `preprocessing.ipynb` to learn text preprocessing techniques
2. Continue with `bag_of_words.ipynb` to implement vectorization
3. Use `tweets_train.txt` as sample data for exercises

## Dependencies

- pandas - Data manipulation and analysis
- scikit-learn - Machine learning library
- nltk - Natural language toolkit
- tabulate - Pretty-print tabular data

## Learning Objectives

- Understand text preprocessing pipeline
- Implement tokenization and stemming
- Apply bag-of-words vectorization
- Work with real-world text data
