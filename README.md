# fake_news_prediction_dsproject

# Data Science project

download news.csv dataset from kaggel for this project

In this project , we train and test the data to detect fake news by using the news.csv dataset
We also used little bit of NLP here i.e., TfidfVectorizer
"TfidfVectorizer - Transforms text to feature vectors that can be used as input to estimator. vocabulary_ Is a dictionary that converts each token (word) to feature index in the matrix, each unique token gets a feature index."

## we used Passive Agressive Model because our dataset is large with string type dataset and in 
## general fake news are continuous data.

  * Passive: If the prediction is correct, keep the model and do not make any changes. i.e., the 
    data in the example is not enough to cause any changes in the model.
    
  * Aggressive: If the prediction is incorrect, make changes to the model. i.e., some change to 
    the model may correct it.


