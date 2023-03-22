Convolutional Neural Network for Predicting Image Types (Dataset: CIFAR-10)

This project uses a convolutional neural network to predict the type of images in the CIFAR-10 dataset. This data set contains 60,000 32x32 pixel color images, divided into 10 different classes.

First, the CIFAR-10 dataset is loaded using the Keras library. It is divided into training and test sets, and information about the size and number of samples in each set is displayed. The unique values of each class in the training set are also shown.

The classes are then filtered to use only the first three (airplane, car, and bird) and updated information about the data sets is displayed.

Next, the Matplotlib library is used to display one of the training images along with its class.

Then the convolutional neural network model is defined using the Keras library. The model consists of several convolutional layers, a smoothing layer, a dense layer, and a softmax activation layer for the output. The "categorical_crossentropy" loss function and the "adam" optimizer are used to compile the model.

Finally, the model is trained using the training data set and its accuracy is evaluated on the test data set. The loss and precision obtained during training are displayed, and the loss and precision are printed on the test data set.