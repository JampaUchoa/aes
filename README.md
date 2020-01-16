Attention-based Recurrent neural network for automatic essay scoring

The code is based keras.
The keras version is 1.1.1, and theano version is 0.8.2.

Kaggle https://www.kaggle.com/c/asap-aes/data
Glove https://nlp.stanford.edu/projects/glove/

import nltk
nltk.download('punkt')

KERAS_BACKEND=theano bash hi_LSTM-CNN.sh 300 1 1 glove