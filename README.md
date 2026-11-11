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
- 
Preprocessing

The following preprocessing steps were applied:
- Text cleaning
- Slang normalization
- Stopword removal while preserving negation words


Modeling & Evaluation

TF-IDF was used for feature extraction. Two machine learning algorithms were compared: Multinomial Naive Bayes and Logistic Regression.

Logistic Regression was selected as the best model based on Macro F1-Score.

Accuracy : 77.56%
Macro F1-Score : 0.62


Conclusion & Limitations
Logistic Regression achieved an accuracy of 77.56% and a Macro F1-Score of 0.62. The model performed best on positive reviews but struggled to classify neutral reviews.

Limitations
- Dataset has an imbalanced sentiment distribution, especially in the neutral class.
- Sentiment labels are derived from user ratings, not manual text annotation.
- Some reviews may contain ambiguous or informal language.
- Model performance on neutral sentiment remains relatively low.


Visualizations

Sentiment Distribution
![Sentiment Distribution](./results/sentiment_distribution.png)

Confusion Matrix
![Confusion Matrix](./results/confusion_matrix.png)
