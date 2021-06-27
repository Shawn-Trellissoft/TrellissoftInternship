This python notebook contains models trained with and without GloVe embeddings, that is used to classify IMDB movie reviews as either positive or negative.

A 4 Layer Convolutional Nueral Network was implemented.
The Optimizer used was rmsprop.
The Loss function used was binary_crossentropy.
The IMDB Reviews Dataset consisted of 66682 unique tokens iterated over 12 epochs in batch size of 64.

The statistics of training a model without using glove embeddings is as follows:
Training Accuracy - 0.99
Training Loss - 0.02
Validation Accuracy - 0.82
Validation Loss - 0.83

The statistics of training a model using pretrained glove embeddings is as follows:
Training Accuracy - 0.99
Training Loss - 0.03
Validation Accuracy - 0.92
Validation Loss - 0.52




