# Spam-SMS-detection
STEPS:
Data Preprocessing, Feature Vector and Models Used:

1)The Dataset had two columns: 1 st containing the class of data ham or spam
and 2 nd containing a string which is the text.

2) All English Stop Words were imported from NLTK and were removed if found
in the sentences.

3) We used a basic Count vectorizer from Sklearn library in order to tokenize and
vectorize the string of text. The Count Vectorizer provides a simple way to both
tokenize a collection of text documents and build a vocabulary of known words,
but also to encode new documents using that vocabulary.
It can be used as follows:
a) Create an instance of the CountVectorizer class.
b) Call the fit() function in order to learn a vocabulary from data.text.
c) Call the transform() function as needed to encode each as a vector.
An encoded vector is returned with a length of the entire vocabulary and an
integer count for the number of times each word appeared in the text.

4) We got our numeric or real feature vector from a string of text messages.
5) We next perform the test train split in the ratio of 70:30, we select the samples
randomly.
6) We feed the X_train, X_test, y_train, y_test to different ML models namely,

ALGORITHMS USED:
Multinomial naïve bayes, Support vector machines, K nearest neighbours,
Random forest.
