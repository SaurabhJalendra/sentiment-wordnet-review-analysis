# Sentiment Analysis with WordNet and SentiWordNet

## Problem Statement

This project implements sentiment analysis on movie reviews using WordNet and SentiWordNet. The tasks include:

1. Processing movie review data:
   - Load the movie review dataset
   - Preprocess text by removing punctuations, numbers, special characters, and stop words
   - Normalize reviews using lemmatization
   - Calculate sentiment scores using SentiWordNet

2. Demonstrate WordNet features including:
   - Synsets (sets of synonyms representing different senses of a word)
   - Synonyms and antonyms extraction
   - Hyponyms (more specific terms) and hypernyms (more general terms)
   - WordNet path similarity (semantic relatedness between words)
   - Word sense disambiguation using the Lesk algorithm

## Project Description

This project analyzes sentiment in movie reviews using natural language processing techniques. It leverages WordNet (a lexical database of English) and SentiWordNet (a lexical resource for sentiment analysis) to understand and quantify the sentiment expressed in text.

The implementation follows these steps:

1. **Data Loading**: The dataset contains movie reviews and their sentiment labels (positive/negative).

2. **Text Preprocessing**:
   - Remove punctuations, numbers, and special characters
   - Convert text to lowercase
   - Remove common stop words that don't contribute to sentiment

3. **Text Normalization**: Apply lemmatization to reduce words to their base forms, ensuring different variations of the same word are treated as a single entity.

4. **Sentiment Analysis**: Use SentiWordNet to calculate sentiment scores for each review by:
   - Extracting positive and negative sentiment scores for each word
   - Calculating the net sentiment (positive score minus negative score)

5. **WordNet Demonstrations**: Showcase various WordNet features to understand semantic relationships between words.

### Requirements

- Python 3.x
- NLTK (Natural Language Toolkit)
- pandas
- Jupyter Notebook

### Dataset

The dataset contains 40,000 movie reviews with binary sentiment labels (positive/negative).

### Implementation

The code is implemented in a Jupyter notebook which provides a step-by-step walkthrough of the sentiment analysis process, including detailed explanations and visualizations of the results.