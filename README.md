# Classification-with-multilayer-perceptron
Supervised learning to classify different regions in a given landscape, from a satellite image of the landscape.
Images are in .raw format of dimensions 1016X1485.
Pixel values are taken in a numpy array.
.csv file is created with labels and pixel values from 4 radar images and one SAR image.
The perceptron has 3 layers, one input layer, one hidden layer, one output layer
keras library is being used for building the perceptron.
Input data has 5 dimensions.
Hidden layer has 128 nodes, activation function used is relu
Output layer has 12 nodes for 12 classes, activation function used is softmax
categorical crossentropy function is used as loss function
optimizer used is adam
