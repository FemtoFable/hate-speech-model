# hate-speech-model

The Jupyter Notebook Code_G8.ipynb file is designed to be run in Google Colab using Python 3.9.16.
Both the exploration/preprocessing and model building are integrate into a single file. 

## Requirements:

To run this notebook in Google Colab, make sure 
to install the necessary libraries using the following commands:

!pip install umap-learn
!pip install keras_tuner

Other libraries are pre-installed in Google Colab.

The notebook relies on the following input files in the Google Colab Content directory 
or in a directory of your choice:

## Data set:

train_en.tsv 
dev_en.tsv   
test_en.tsv  

## Trained model:

0.59_fin.h5  


## Imports:

The notebook uses the following libraries:

NumPy
Pandas
Matplotlib
Seaborn
TensorFlow
Keras
NLTK
Gensim
UMAP
TextBlob
scikit-learn
Keras Tuner

It also uses the Universal Sentence Encoder, which can be found at:
https://tfhub.dev/google/universal-sentence-encoder/4
