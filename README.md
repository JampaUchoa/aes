
# Attention-based recurrent neural network for automatic essay scoring

**This project requires *Python 2.7***

## Installation

1. Clone this repository
`git clone https://github.com/JampaUchoa/aes.git`
2. Install the requirements
`pip install -r requirements.txt`
3. Install Punkt
```
import nltk
nltk.download('punkt')
```
4.  Download Glove dataset of word embeddings [the Stanford project](https://nlp.stanford.edu/projects/glove/)
5. Compress the dataset using gzip
 `gzip glove.6B.300d.txt`
6. Insert the dataset `glove.6B.300d.txt.gz` inside embeds/ folder
5. Sign in and download the [dataset of the Kaggle competition](https://www.kaggle.com/c/asap-aes/data)
6. Split the file `training_set_rel3.tsv` into `dev.tsv` `test.tsv` and `train.tsv` and insert them into the `data/` folder.
7. Run the code with the following command 
`KERAS_BACKEND=theano bash hi_LSTM-CNN.sh 300 1 1 glove`