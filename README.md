# My_DeepLearning_Projects
This is my first Git Repository
<br>
Author- Shaik Imran
<br>
In this project i created and trained a convolutional neural network (CNN) for image classification using TensorFlow and Keras.

 I taken the CIFAR-10 dataset and normalized the pixel values, which is a common preprocessing step when working with image data. The pixel values are scaled to be between 0 and 1, which helps the neural network converge faster during training.

 The code defines a sequential convolutional neural network (CNN) using Keras with three convolutional layers, each followed by max-pooling.
The model processes 32x32 RGB images and includes ReLU activation functions for convolutional layers and dense layers.
After the convolutional layers, a flattening layer is added, followed by a dense layer with 64 units and ReLU activation.
Another dense layer with 10 units is added, representing the output layer for a classification task (adjust units based on the number of classes).




The model is compiled using the Adam optimizer, which is considered one of the best adaptive optimizers in many cases. The loss function is set to sparse categorical crossentropy, suitable for integer-encoded class labels.
The model is trained using the fit function for 10 epochs, iterating over the training data. The training progress and validation performance are tracked using the provided validation data.

