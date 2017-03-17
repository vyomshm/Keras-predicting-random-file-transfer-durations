# Keras-predicting-random-file-transfer-durations
Jupyter notebooks to create random file transfer data on an ElasticSearch Cluster in order to train a neural network to predict the file transfer duration.

Cluster already exists, so there's no need running the random online generator notebook again. STart with json preprocessing notebook before you run the Keras model because the training and testing dataset it uses, will be created only after you've run the code in the preprocessing notebook.

## Note:

My elasticsearch cluster is hosted on an older version of the ElasticSearch (v-1.7). To make sure this code runs you will need to downgrade your elasticsearch-py version in your environment. You can install the correct version by running :

`pip install -r requirements.txt`

after you've cloned this repository.