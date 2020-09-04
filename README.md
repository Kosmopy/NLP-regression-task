# NLP-regression-task
Predicting how many claps an article posted on medium.com will receive based on text and meta features

Data science enables us to extract knowledge and insights from  different types of data. Given the increase in textual data which is available on the internet/social media and the possibility to scrap those data resources, Natural Language Processing (NLP) is a growing field in data science. NLP allows us to use features from text and word embeddings in our computations and algorithms.
The database for this regression task are blog articles which were posted on medium.com, a widely used platform for data science knowledge exchange. In this notebook, we will utilize text data and provided and generated meta data to predict the number of *Claps* (equivalent to *Likes*) an article receives. To solve this regression task we will (1) preprocess the data, both, the text and the meta data, (2) extract some additional features from the data, including features that require some more elaborated approaches, for instance topic modeling, (3) apply GloVe embeddings to our text data and, eventually, train neural networks. Our first neural network will be only trained beased on the non-text features and our final model will have mixed inputs, including the word embedding. With our final model we will (4) make predictions of the number of Claps the articles in our test set receive. Eventually, we will (5) conclude and summarize our learnings.


**Table of Contents**

1. Text Cleaning and Preprocessing

2. Feature Engineering
2.1 Meta features
2.2 Dictionary based Sentiment Analyser
2.3 Bag of Words based features
2.4 Topic modeling with Word2Vec

3. Neural Network Modeling
3.1 Basic model
3.2 Mixed input model

4. Predictions
4.1 Preparation of prediction dataset
4.2 Prediction and submission preparation

5. Conclusion

References
