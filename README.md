# Fake News Detection

## 1. Dataset

Kaggle link: https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification

(WELFake) is a dataset of 72,134 news articles with 35,028 real and 37,106 fake news. For this, authors merged four popular news datasets (i.e. Kaggle, McIntire, Reuters, BuzzFeed Political) to prevent over-fitting of classifiers and to provide more text data for better ML training.

Dataset contains four columns: Serial number (starting from 0); Title (about the text news heading); Text (about the news content); and Label (0 = fake and 1 = real).

There are 78098 data entries in csv file out of which only 72134 entries are accessed as per the data frame.

Published in:
IEEE Transactions on Computational Social Systems: pp. 1-13 (doi: 10.1109/TCSS.2021.3068519).

## 1.1 EDA

- Target Label Distribution:

![](https://github.com/tmishinev/fake-news-detection/blob/main/snapshots/target.PNG)

- Word Counts Distribution:

![](https://github.com/tmishinev/fake-news-detection/blob/main/snapshots/word_dist.PNG)








## 2. Notebooks:

## 2.1 fake-news-lstm-baseline.ipynb - LSTM baseline 

https://www.kaggle.com/code/tmishinev/fake-news-lstm-baseline-97-accuracy

- Classification Report

![alt text](https://github.com/tmishinev/fake-news-detection/blob/main/snapshots/lstm_classif.PNG)

- Confusion Matrix

![alt text](https://github.com/tmishinev/fake-news-detection/blob/main/snapshots/lstm_conf.PNG)


## 2.2 fake-news-keras-bert.ipynb - Keras/BERT implementation

https://www.kaggle.com/code/tmishinev/fake-news-keras-bert/data

- Classification Report

![alt text](https://github.com/tmishinev/fake-news-detection/blob/main/snapshots/bert_classif.PNG)

- Confusion Matrix

![alt text](https://github.com/tmishinev/fake-news-detection/blob/main/snapshots/bert_conf.PNG)



