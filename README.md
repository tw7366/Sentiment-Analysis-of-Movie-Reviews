# Sentiment-Analysis-of-Movie-Reviews

### About
NLP project


### Objective
Through sentiment analysis, distinguish whether movie reviews are positive or negative

### Library
* [Tensorflow](https://www.tensorflow.org/)
* [pandas](https://pandas.pydata.org/pandas-docs/stable/user_guide/index.html#user-guide)
* [numpy](https://numpy.org/)
* [nltk](https://www.nltk.org/)

### Algorithm
* [The Sequential Model](https://keras.io/guides/sequential_model/)
* [Embedding](https://keras.io/api/layers/core_layers/embedding/)
* [LSTM](https://keras.io/api/layers/recurrent_layers/lstm/)

### Result
With embedding & GlobalAveragePooling1D :
![Embedding](https://i.imgur.com/5WvwcIs.png)

With embedding & LSTM
![LSTM](https://i.imgur.com/cpuNcqU.png)

The model with GlobalAveragePooling1D has outperformed the one with LSTM.

Both models start overfitting after 6 epoches, so the numbers of epoch have been kept low.

### Reflection
I tried my best to minimize the validation loss by adjusting the number of hidden layers, nodes, and epochs; however, it didn't go lower than 0.24.
