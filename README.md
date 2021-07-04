Twitter samples from NLTK dataset is used as training set. 
Firstly, data is preprocessed to remove unwanted words and symbols and preserve significant ones. 

A frequeny dictionary is built as {(word,class): freq. of word in class}. 
Logistic regression method is used to classify a tweet as 1 (+ve) or 0 (-ve). 
The algorithm uses Gradient descent method to minimize error in each iteration of training.

Test accuracy is 99.5%.
