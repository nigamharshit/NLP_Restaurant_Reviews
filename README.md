# NLP_Restaurant_Reviews
Restaurant Reviews through Natural Language Processing

Here first we had perform text preprocessing on reviews and then with CountVectorizer convert the review into array and then with the help of DecisionTreeClassifier predict weather the review is positive or negative<br>

1 represent Positive Review<br>
0 represent Negative Review<br>

CountVectorizer is a great tool provided by the scikit-learn library in Python.
It is used to transform a given text into a vector on the basis of the frequency (count) of each word that occurs in the entire text.
This is helpful when we have multiple such texts, and we wish to convert each word in each text into vectors (for using in further text analysis)

# Code Requirements
python 3.x with following modules installed<br>

numpy<br>
pandas<br>
import re<br>
import nltk<br>

# Accuracy
It achieve an accuracy of 72.8 % on test data.
