# Sentiment Analysis Using LSTM

Welcome to my Sentiment Analysis project using LSTM! This project focuses on building a powerful text classification model leveraging natural language processing (NLP) techniques and deep learning. The primary goal is to accurately predict sentiment from text data.

## Project Overview
In this project, I tackled the full pipeline of sentiment analysis, from data cleaning to model deployment. Below is a step-by-step breakdown of the workflow:

### 1. Data Cleaning
- Checked for missing values and duplicates to ensure the dataset's integrity.
  
### 2. Data Distribution
- Visualized label categories using value counts and Matplotlib to understand class distribution.

### 3. Text Preprocessing
- Developed custom functions to clean text by removing links, punctuation, hashtags, and stopwords.
- Applied stemming to reduce words to their base forms.

### 4. Normalization
- Combined preprocessing steps into a single normalization function and applied it to the entire dataset.

### 5. Word Cloud Visualization
- Created word clouds to highlight key terms within each category, providing insight into the dataset post-cleaning.

### 6. Data Splitting
- Divided the dataset into training and test sets using `train_test_split` for model evaluation.

### 7. Tokenization and Padding
- Tokenized the text to create a vocabulary.
- Converted text to sequences and padded them to ensure consistent input lengths.

### 8. Pre-trained Word Embeddings
- Integrated GloVe-Twitter-200 embeddings using Gensim to enrich the model with pre-trained word vectors.

### 9. Embedding Matrix
- Constructed an embedding matrix to serve as weights in the embedding layer of the model.

### 10. Model Architecture
- Built the model with the following layers:
  - Embedding layer
  - Two LSTM layers for sequence learning
  - Dropout layers for regularization
  - Dense layer with softmax activation for classification

### 11. Model Training
- Compiled the model and trained it on the processed dataset, optimizing for accurate sentiment classification.

### 12. Prediction Pipeline
- Developed a prediction pipeline to process new input text and output sentiment category predictions along with probability scores.

## Conclusion
This project provides a comprehensive framework for sentiment analysis using LSTM, combining effective preprocessing, visualization, and modeling techniques. Feel free to explore the code and experiment with the model!

