# NEWS-CATEGORY-CLASSIFICATION

News Category Classification through multiple machine learning and Deep learning models.

### Models implemented:

* Naive Bayes Classifier
* SVM Classifier
*  Random Forest Classifier
* Decision Tree Classifier
* Logistic Regression(LR) Classifier
* MLP Classifier
* Convolutional Neural Network (CNN)
* Reccurent Neural Network (RNN)-Long Short-Term Memory (LSTM)
* Bidirectional RNN

### Metrics used to evaluate the performance of models:

* Precision
* Recall
* F1 Score
* Accuracy

We evaluate each classifier's ability to predict the category for given an article’s. 
These metrics were used to calculate the results.

### Feature Extraction Techniques:

The collection of text documents is converted to a matrix of token counts using count vectorize that produces a sparse representation of the counts.

TFIDF,term frequency–inverse document frequency, is the statistic that is intended to reflect how important a word is to a document in our corpus. This is used to extract the most meaningful words in the Corpus.

### Packages required:

* Pandas
* sklearn
* Numpy

### Classifier that got highest Accuracy:

*SVM model at character level was proven to be the best among
the 6 supervised learning models in correctly categorizing news articles*

  Categories |     Precision |        Recall |      F1-Score |       Support | Accuracy 
------------ | ------------- | ------------- | ------------- | ------------- | ------------- 
Business     | 1.00          | 1.00          |      1.00     |    800        | 99.58%
Entertainment| 1.00          | 1.00          |      1.00     |    818        | 99.58%
Sports       | 1.00          | 0.99          |      1.00     |    781        | 99.58%   

*In Deep Learning Models Bidirectional RNN achieves the highest accuracy*

  Categories |     Precision |        Recall |      F1-Score |       Support | Accuracy 
------------ | ------------- | ------------- | ------------- | ------------- | ------------- 
Business     | 0.99          | 1.00          |      1.00     |    799        | 99.3%
Entertainment| 0.99          | 0.99          |      0.99     |    816        | 99.3%
Sports       | 0.99          | 0.99          |      0.99     |    784        | 99.3%   



