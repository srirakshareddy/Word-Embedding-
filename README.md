# Word-Embedding-

In this project I am variety of machine learning techniques to classify messages (SMS or Tweets) into Spam or Ham. This project is an exercise for text classification which is one of the most common natural language processing tasks. I am using two methods of
classifications:
1. Traditional Machine Learning Classifiers from SKLearn:
from sklearn.linear_model import LogisticRegression
from sklearn.svm import SVC
from sklearn.naive_bayes import MultinomialNB
from sklearn.tree import DecisionTreeClassifier
from sklearn.neighbors import KNeighborsClassifier
from sklearn.ensemble import RandomForestClassifier

2. Word Embedding Layers with Deep Learning. For word embedding I am using Glove model:
https://nlp.stanford.edu/projects/glove/
https://medium.com/analytics-vidhya/basics-of-using-pre-trained-glove-vectors-in-python-d38905f356db


Dataset: 
1. UCI Dataset:
https://archive.ics.uci.edu/ml/datasets/Spambase
2. Glove model dataset:
https://www.kaggle.com/danielwillgeorge/glove6b100dtxt
