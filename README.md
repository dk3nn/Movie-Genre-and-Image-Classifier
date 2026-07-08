# Movie-Genre-and-Image-Classifier
Two sepertate projects

## Move Genre Classifier
Classifies IMDb movie descriptions into 20 different genres using an LSTM neural network with pre-trained GloVe word embeddings.
Due to the limited data set (1000 samples across the 20 genres) the models overfit. The training accuracy improves but the test accuracy remains low, with a larger dataset better test accuracy would be expected.
## Image Classifier
Classifies images into 6 categories using a convolutional neural network, trained using the Intel Image Classifiction dataset which includes 14000 images.

## Stack
Python, TensorFlow/Keras, NumPy, scikit-learn, NLTK, Matplotlib
