## Fake news classification using Lstm, Bidirectional Lstm and also Passive-aggresive Model

download news.csv dataset from https://www.kaggle.com/samridhisuri/newscsv for this project.

>In Fakenews_lstm.ipynb notebook
 * We used NLP for preprocessing data
 * developed and trained 2 models  : 
                                    1. model = lstm
                                    2. model1 = Bidirectional lstm
                                   
**Long short-term memory** (LSTM) is an artificial recurrent neural network (RNN) architecture[1] used in 
the field of deep learning. Unlike standard feedforward neural networks, LSTM has feedback connections. It 
can not only process single data points (such as images), but also entire sequences of data (such as speech or video). 

**Bidirectional LSTMs** are an extension of traditional LSTMs that can improve model performance on sequence 
classification problems. In problems where all timesteps of the input sequence are available, Bidirectional
LSTMs train two instead of one LSTMs on the input sequence. 
 



>In fakenew.ipynb note book:
* We used little bit of NLP here i.e., TfidfVectorizer
* **TfidfVectorizer** - Transforms text to feature vectors that can be used as input to estimator. vocabulary_ Is a dictionary that converts each token (word) to feature index in the matrix, each unique token gets a feature index."

* We used Passive Agressive Model because our dataset is large with string type dataset and in general fake news are continuous data.

  * **Passive**: If the prediction is correct, keep the model and do not make any changes. i.e., the 
    data in the example is not enough to cause any changes in the model.
    
  * **Aggressive**: If the prediction is incorrect, make changes to the model. i.e., some change to 
    the model may correct it.


