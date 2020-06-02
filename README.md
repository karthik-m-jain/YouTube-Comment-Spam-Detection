# YouTube-Comment-Spam-Detection

## Abstract
 1. Classifying YouTube comments as it attracts malicious users and is a challenge since messages are short and rife with slangs,  symbols and abbreviations.
 2. Using Text classification and prediction model to predict YouTube comments are spam or not.
 3. Using bag-of-words and different machine learning algorithms for prediction
 4. Preprocessing the data to remove punctuations, plurals, to remove stop words, to record binary counts.
 5. Comparing various classification techniques and statistical analysis of results.

## Dataset Description
 Source:
 This corpus has been collected using the YouTube Data API v3.

 Data Set Information:
 The table below lists the datasets:

 Dataset --- YouTube ID -- # Spam - # Ham - Total
 Psy ------- 9bZkp7q19f0 --- 175 --- 175 --- 350
 KatyPerry - CevxZvSJLk8 --- 175 --- 175 --- 350
 LMFAO ----- KQ6zr6kCPj8 --- 236 --- 202 --- 438
 Eminem ---- uelHwf8o7_U --- 245 --- 203 --- 448
 Shakira --- pRpeEdMmmQ0 --- 174 --- 196 --- 370

 Attribute Information:
 The collection is composed by one CSV file per dataset, where each line has the following attributes:

 COMMENT_ID,AUTHOR,DATE,CONTENT,TAG

 One example bellow:
 z12oglnpoq3gjh4om04cfdlbgp2uepyytpw0k,Francisco Nora,2013-11-28T19:52:35,please like :D [Web Link],1

## Machine Learning Models

 The data was converted into numeric form using both CountVectorizer and TfidfVectorizer. The models were analyzed using data obtained   by train test split method and cross-validation. The following list of models were used for classification and clustering. 

 1. Classification techniques used:
 2. MultinomialNB Classifier
 3. BernoulliNB Classifier
 4. Decision Tree Classifier (criterion='entropy')
 5. K-nearest Neighbor Classifier (n_neighbors=5)
 6. Random Forest Classifier
 7. Voting Classifier
 8. Gradient Boosting Classifier

 Clustering technique used:
 1. KMeans Clustering (n_clusters=5)


