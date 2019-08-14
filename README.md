# Image-Captioning
•	The goal of image captioning is to convert a given input image into a natural language description. The encoder-decoder framework is widely used for this task. The image encoder is a convolutional neural network (CNN). In this repository, we used [InceptionV3](https://keras.io/applications/) model to vectorize the [Flicker30k](https://www.kaggle.com/hsankesara/flickr-image-dataset) dataset. The decoder is a long short-term memory (LSTM) network. Also, we used pre-trained [GloVe](https://nlp.stanford.edu/projects/glove/) word embeddings for the embedding layer.



![Architecture](/arch.png)
