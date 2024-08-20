
# Fake News Detection System

**Overview:**

This system uses machine learning to detect fake news articles. It leverages natural language processing techniques to analyze news articles' text and classify them as authentic or fake. Two primary text representation techniques are used in the present project: bag-of-words (BoW) and TF-IDF, combined with models such as Multinomial Naive Bayes and Passive Aggressive Classifier for this classification task.



## Features

- Text Preprocessing: Includes cleaning the text data by removing special characters, numbers, and stopwords, followed by stemming.
- Text Representation: Utilizes CountVectorizer (BoW) and TF-IDF vectorization to convert text data into feature vectors.
- Machine Learning Models: Implements and compares the performance of Multinomial Naive Bayes and Passive Aggressive Classifier algorithms.
- Evaluation Metrics: Accuracy, Precision, Recall, F1-Score, and Confusion Matrix are used to evaluate model performance.
- Sample Prediction: Demonstrates the prediction of a news article as either authentic or fake using a test dataset.
## How it works

- Data Preprocessing: The text is cleaned, stopwords are removed, and words are stemmed using NLTK's PorterStemmer.
- Vectorization: The cleaned text data is transformed using CountVectorizer (BoW) and TF-IDF.
- Model Training and Evaluation:
    - Multinomial Naive Bayes: Trained and evaluated using both BoW and TF-IDF features.
    - Passive Aggressive Classifier: Trained and evaluated using both BoW and TF-IDF features.
    - The models are evaluated using accuracy, precision, recall, F1-score, and confusion matrix.
- Prediction on New Data: The trained model is used to predict whether a news article is authentic or fake.

## Author

- [Suprit Patil](https://github.com/ssp964)

