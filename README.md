# Text Analysis of r/MyBoyfriendIsAI

## Overview
This project explores sentiment analysis and topic modeling on **1,000 Reddit posts** from the subreddit **r/MyBoyfriendIsAI**, applying machine learning and deep learning techniques using PyTorch.

The objective is to understand emotional expression patterns and thematic structure in AI relationship discussions.


## Methods

### Machine Learning & NLP Techniques
- **K-Means Clustering** using PyTorch tensors and `CountVectorizer`
- **Sentiment Analysis** using NLTK’s `SentimentIntensityAnalyzer`
- **Deep Embedding Clustering (DEC)** using a Variational Autoencoder (VAE) for latent space representation
- **Dimensionality Reduction**
  - PCA – reduces noise and improves efficiency
  - t-SNE – effective for small datasets
  - UMAP – faster and more suitable for large datasets (chosen as primary)
- **LDA Topic Modeling** using Gensim for extracting dominant themes

## Project Context
This work was developed as part of the **Data Infrastructure Group lab**, with the aim of gaining practical experience in:
- PyTorch-based text analysis
- Unsupervised clustering methods
- Dimensionality reduction and embedding space visualization
- Sentiment extraction and topic inference

