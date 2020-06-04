# Tweets-Classification-among-Hate-Speech-Offensive-Neither
Twitter Dataset was used to classify the tweets as Offensive, Hate Text, and Neither of them. After Sampling and Balancing the T-Davidson Dataset taken from GITHUB 35,929 tweets are used to train Machine Learning and Deep Learning Models. The models were built using Scikit-Learn and Keras API in Python.

TF-IDF Vectors were formed with 8,000 most frequent words and were used as features for building the Machine Learning Models.

Their Accuracy and F1 Scores:
SVM:                 93%   F1-Score: 93

Logistic Regression: 91%   F1-Score: 91.3

SGD Classifier:      86%   F1-Score: 85.65

Word2Vec Embeddings of 32 Dimensions were trained and used as the input features to build the Sequence Model consisting of Simple RNN and Dense Layer.

Training Accuracy: 98.39 %

Validation Accuracy: 96.25%

Test Accuracy: 95.99%

F1-Score: 96

