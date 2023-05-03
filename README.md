# Fashion MNIST Classifier
This project is a simple classification task on the Fashion MNIST dataset using TensorFlow and Keras. 
The goal is to build a neural network model that can accurately classify images of different clothing items.

## Dataset
The Fashion MNIST dataset consists of 70,000 grayscale images of 10 different clothing items, each with 28x28 pixels. 
The dataset is split into 60,000 training images and 10,000 test images. 
The images are labeled with integers ranging from 0 to 9, representing the different clothing categories:

| Class | Description |
| ----- | ----------- |
| 0     | T-shirt/top |
| 1     | Trouser     |
| 2     | Pullover    |
| 3     | Dress       |
| 4     | Coat        |
| 5     | Sandal      |
| 6     | Shirt       |
| 7     | Sneaker     |
| 8     | Bag         |
| 9     | Ankle boot  |

## Code
The code for this project is written in Python using the following libraries:

* TensorFlow
* Keras
* NumPy
* Matplotlib
* Pandas

The fashion_mnist dataset is loaded using Keras, and the images are normalized to have pixel values between 0 and 1. 
The model architecture consists of a flattened input layer, a hidden layer with 128 neurons and ReLU activation, 
and an output layer with 10 neurons and softmax activation.

The model is trained using the Adam optimizer and sparse categorical cross-entropy loss. 
After training for 10 epochs, the model achieves an accuracy of around 88% on the test set.

Finally, the model is used to predict the labels of some test images, and the actual and predicted labels are displayed along with the images.

## Usage
To run this project, you can simply copy and paste the code into a Python file or a Jupyter Notebook. 
Make sure to have the required libraries installed before running the code.

The code can be modified to experiment with different model architectures, optimization algorithms, and hyperparameters. 
You can also try to improve the accuracy of the model by adding more layers, changing the activation functions, or using data augmentation techniques.

## License
This project is licensed under the MIT License.
