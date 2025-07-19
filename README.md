# Final_project
fake news detection system using NLP
The Fake News Detection System is a machine learning-based application designed to identify whether a news article is real or fake. It uses Natural Language Processing (NLP) techniques to clean and analyze the text of news articles and applies a Naive Bayes classifier to predict the label of each article.

The system starts by loading a dataset of real and fake news. It then performs text preprocessing, such as:

Converting to lowercase,

Removing punctuation and URLs,

Removing stopwords,

Applying lemmatization.

After cleaning the data, it uses TF-IDF vectorization to convert text into numerical features, which are then used to train a classification model.

Finally, the model is evaluated using metrics like accuracy, classification report, and confusion matrix. This helps understand how well the system distinguishes between fake and real news.
