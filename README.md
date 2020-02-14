# Chatbot-with-Deep-Learning
Develop a deep learned chatbot to answer various customer queries

# Libraries used for designing the chatbot
1.Tensorflow
2.Tflearn
3.Numpy
4.nltk
5.json
6.pickle

# Natural Language processing techniques used in cleaning the data

1.Stemming: This technique is used to convert the words to thier root forms because a word in plural form doesn't hold any meaning for the model to understand.

2.Lemmatization: Lemmatization is the process of grouping together the inflected forms of a word so they can be analysed as a single item. Generally lemmatization and Stemming has been found to be similar but in practice, we use lemmatization as it has been found to be more effective.


# Deep Learning model

Tflearn is a part of tensorflow which has been used here to build the chatbot's model for training data , which are questions and answers present in the intents.json file, Generally Adam is used as an optimizer.
Our deep learning model contains an input layer, fully connected layer and the output layer at the end.


