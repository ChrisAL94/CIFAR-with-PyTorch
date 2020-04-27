# CIFAR CNN with PyTorch
*Code for a CIFAR Classifier with PyTorch*

## CIFAR-10 dataset

The CIFAR-10 dataset consists of 60000 32×32 colour images in 10 classes, with 6000 images per class. 
There are 50000 training images and 10000 test images.
The dataset is divided into five training batches and one test batch, each with 10000 images. 
The test batch contains exactly 1000 randomly-selected images from each class. 
The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. 
Between them, the training batches contain exactly 5000 images from each class.

Here are the classes in the dataset, as well as 10 random images from each:

![alt text](https://pytorch.org/tutorials/_images/cifar10.png)


## Training an Image Classifier in Pytorch


    Load and normalizing the CIFAR10 training and test datasets using torchvision
    Define a Convolution Neural Network
    Define a loss function
    Add GPU and CUDA support
    Train the network on the training data
    Test the network on the test data


## Software and Libraries

This project uses the following software and Python libraries:

* [Python](https://www.python.org/downloads/release/python-364/)
* [NumPy](http://www.numpy.org/)
* [PyTorch](https://pytorch.org/)
* [matplotlib](https://matplotlib.org/)
