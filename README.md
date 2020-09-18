# Classification-with-multilayer-perceptron
Supervised learning to classify different regions in a given landscape, from a satellite image of the landscape.
Images are in .raw format of dimensions 1016X1485.
Test1016x1485.raw and Train1016x1485.raw is used for labels
The other five images are used for pixel values which are being used as input parameters.
Pixel values are taken in a numpy array.
.csv file is created with labels and pixel values from 4 radar images and one SAR image.
The perceptron has 3 layers, one input layer, one hidden layer, one output layer
keras library is being used for building the perceptron.
Input data has 5 dimensions.
Hidden layer has 128 nodes, activation function used is relu.
Output layer has 12 nodes for 12 classes, activation function used is softmax.
Categorical crossentropy function is used as loss function.
Optimizer used is adam.
Classes 13, 14, 9 are being excluded because of their low total count.
