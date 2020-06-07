# Image-Classifier-
This image classifier is made using Tensorflow and Keras.Building and training a model that classifies CIFAR-10 dataset images that were loaded using Tensorflow Datasets which consists of dogs, cats and other 8 objects using Tensorflow and Keras libraries in Python.

The dataset will be partitiond into 50000 samples for training data, and 10000 samples for testing data.
Each sample is an image of 32x32x3 pixels (width and height of 32 and 3 depth which are RGB values). 
The model has 3 layers of 2 ConvNets with a max pooling and ReLU activation function and then a fully connected with 1024 units.
