
# EMNIST Character Recognition

This project builds a Convolutional Neural Network (CNN) using PyTorch to recognize handwritten characters from the EMNIST dataset. EMNIST extends the popular MNIST dataset by including letters and digits, making it suitable for character recognition tasks across 47 classes.

### Features:

* CNN with three convolutional layers followed by fully connected layers
* Max pooling and ReLU activations after each convolution
* Trained on the balanced split of EMNIST dataset achieving \~87% accuracy
* Modular PyTorch implementation for easy customization and extension

### Dataset:

The model uses the EMNIST Balanced split which contains 47 balanced classes of handwritten characters including digits and letters. The raw dataset files are **not included** due to their large size. You can download them from the [official EMNIST dataset page](https://www.nist.gov/itl/products-and-services/emnist-dataset).

### Usage:

* Clone this repository
* Install required dependencies (PyTorch, torchvision, etc.)
* Download the EMNIST dataset separately and place it in the appropriate data folder (or modify dataset paths in the code)
* Run the training and evaluation scripts to train the model or test its performance

### Note:

Large raw data files are excluded from this repo to comply with GitHub file size limits. The repository contains only code and small supporting files.

