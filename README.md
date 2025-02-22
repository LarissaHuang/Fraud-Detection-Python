# Fraud-Detection-Python
Author: Larissa Huang

This project demonstrates several fraud analysis techniques, including the following:

### Working with imbalanced data

- Highly imbalanced fraud data
- Resampling data 

![minority oversampling comparision](images/SMOTE.png)

- **Tools: SMOTE, scikit-learn, train-test-split, matplotlib**



### Fraud detection with labeled data

- Logistic Regression, Decision Tree, Random Forest
- Performance metrics
- Hyperparamter optimization
- Ensemble methods (model weight adjustments)

![precision recall curve](images/pr-curve.png)

- **Tools: confusion matrix, classification report, roc_auc_score, precision-recall curve, GridsSearchCV, VotingClassifier, Seaborn**


### Fraud detection without labels

- Customer segmentation
- K-means clustering to detect fraud using outliers and small clusters,
- DB-scan clustering

![elbow curve](images/elbow.png)

- **Tools: MiniBatchKMeans, silhouette score, homogeneity score, elbow curve**


### Text mining

- Clean text data (tokenization, stopwords, stemming, lemmatization)
- Flag certain words and topics
- Topic modeling for fraud detection
- Topic visualization

![topic modeling](images/topics.png)

- **Tools: nltk, LDA, bagofwords, doc2bow, pyLDAvis, gensim, corpora**

