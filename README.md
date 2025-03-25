# Urdu Sentiment Analysis Tool

## Overview
This project focuses on developing an automatic sentiment analysis tool for Urdu text from social media platforms. The tool classifies posts into positive, negative, or neutral sentiments to help brands, influencers, and businesses analyze customer feedback and engagement.

## Features
- **Text Preprocessing**: Removes stopwords, punctuation, emojis, and non-informative tokens.
- **Stemming & Lemmatization**: Reduces word variants to their base form.
- **Feature Extraction**: Tokenization, TF-IDF, and Word2Vec-based feature extraction.
- **N-grams Analysis**: Unigram, bigram, and trigram frequency analysis.
- **Sentiment Classification**: Machine learning model for sentiment prediction.
- **Evaluation & Optimization**: Performance metrics and improvement analysis.

## Dataset
The project uses a publicly available Urdu social media dataset (e.g., from Kaggle or Urdu Twitter Sentiment datasets) containing raw posts with sentiment labels.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/muradhameed59/urdu-sentiment-analysis.git
   cd urdu-sentiment-analysis
   ```
2. Download the Urdu dataset and place it in the `data/` folder.

## Usage
Run the Jupyter Notebook to execute the sentiment analysis pipeline:
```sh
jupyter notebook Sentiment_Analysis.ipynb
```

## Tools & Libraries
- Python
- NLTK, spaCy, or Polyglot (text processing)
- Scikit-learn (machine learning)
- Gensim (Word2Vec)
- pandas, matplotlib (data analysis & visualization)

## Expected Output
- Preprocessed Urdu text
- Extracted features (TF-IDF, Word2Vec results)
- N-gram analysis results
- Sentiment classification model with accuracy, precision, recall, and F1-score

## Challenges
- Handling Urdu grammar (SOV structure, morphology, script)
- Noisy data from social media (emojis, spelling variations, incomplete sentences)
- Limited pre-trained NLP resources for Urdu

![Urdu Sentiment Analysis Screenshot](https://github.com/Muradhameed921/Urdu-Sentiment-Analysis/blob/main/O1.jpg)
