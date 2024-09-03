# hse-nlp-project
Sentiment analysis project for NLP course

**Task description**

Classification of sentiment into 5 levels in Russian-language text.

**What was done**

1. Text preprocessing:
    * Clear text from URL's, punctuation, etc;
    * Lowercasing;
    * Tokenization;
    * Deleting stop-words;
    * Lemmatization.
2. Obtaining embeddings using TF-IDF and Doc2Vec models;
3. Training classification models: KNN, SVM, AdaBoost, Gradient Boosting, Random Forest, RNN, GRU, LSTM, Bi-LSTM, CNN.

**Results**

The best model by metrics (f1-score, accuracy) is LSTM, reached accuracy = 0.73.
