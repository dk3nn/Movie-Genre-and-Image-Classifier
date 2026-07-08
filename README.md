# Movie Genre and Image Classifier

Two separate projects.

## Movie Genre Classifier

Classifies IMDb movie descriptions into 20 different genres using an LSTM neural network with pre-trained GloVe word embeddings.

Due to the limited dataset (1,000 samples across 20 genres) the models overfit. Training accuracy improves but test accuracy remains low. With a larger dataset, better test accuracy would be expected.

## Image Classifier

Classifies images into 6 categories using a convolutional neural network, trained using the Intel Image Classification dataset which includes 14,000 images.

## Stack

Python, TensorFlow/Keras, NumPy, scikit-learn, NLTK, Matplotlib
