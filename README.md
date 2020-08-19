# Summer-of-Science--Auto-Image-Captioning-using-CNN-and-LSTM
To make our image caption generator model, we will be merging these architectures. It is also called a CNN-RNN model. 
-> CNN is used for extracting features from the image. The feature extraction model is a neural network that given an image is able to extract the salient features, often in the form of a fixed-length vector. A convolutional neural network is best used as the feature extraction submodel. This network can be trained directly on the images in dataset. 
-> LSTM will use the information from CNN to help generate a description of the image.
