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

I began by importing a few libraries and reading the spambase dataset and removing special characters from the column names to ensure that regression models run properly. Using a few different NLP methods such as
1. LogisticRegression
2. SVC
3. MultinomialNB
4. DecisionTreeClassifier
5. KNeighborsClassifier
6. RandomForestClassifier

I first split the data into training and testing dataset with a 70:30 ratio. Based on the predicted value (x-test) and the actual y-test value, we found the accuracy of each of the methods. Outputs are given below.

Next, I used the GloVe method where pre-trained word vectors are used. I used the tokenizer and then ensured that the max length of words was 4. After creating a weight matrix for the words in the training documents we defined the model, compiled it and summarized the trainable and non-trainable parameters. In the end, we split the data into 80:20 ratio and found the accuracy accordingly.
