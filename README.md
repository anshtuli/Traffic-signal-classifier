This project implements a Convolutional Neural Network (CNN) in Python using Keras and TensorFlow to classify traffic signs from an image dataset. It includes image preprocessing, data augmentation, and model training for accurate recognition of multiple traffic sign classes.

The CNN model consists of:

2 Convolution layers (60 filters, 5x5) + MaxPooling

2 Convolution layers (30 filters, 3x3) + MaxPooling

Dropout for regularization

Fully Connected Layer with 500 neurons (ReLU)

Output Layer with softmax activation for multi-class classification
