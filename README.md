# ml-coba-coba-aja-biar-tau-sikit
Gojek App Review Sentiment Analysis

This project aims to analyze the sentiment of user reviews of the Gojek application using Natural Language Processing (NLP) and Machine Learning techniques.

The analysis classifies user reviews into three sentiment categories:
- Positive (1): Reviews with ratings of 4–5.
- Neutral (0): Reviews with a rating of 3.
- Negative (-1): Reviews with ratings of 1–2.

The project compares Multinomial Naive Bayes and Logistic Regression algorithms using TF-IDF for text feature extraction.

Objectives
- Transform text data into numerical features using TF-IDF.
- Compare machine learning models for sentiment classification.
- Evaluate model performance using classification metrics.


Dataset & Preprocessing

The dataset consists of Indonesian-language user reviews of the Gojek application.

- Initial sample: 5,000 reviews.
- Final dataset: 3,653 unique reviews.
- Positive: 2,288 reviews.
- Negative: 1,152 reviews.
- Neutral: 213 reviews.

Sentiment labels were generated based on user ratings:
- Rating 1–2: Negative (-1)
- Rating 3: Neutral (0)
- Rating 4–5: Positive (1)

Preprocessing

The following preprocessing steps were applied:
- Text cleaning
- Slang normalization
- Stopword removal while preserving negation words
