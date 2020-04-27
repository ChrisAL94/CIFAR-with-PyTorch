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


## Usage

mnist makes it easier to download and parse MNIST files.

To automatically download the train files, and display the first image in the
dataset, you can simply use:

```python
import mnist
import scipy.misc

images = mnist.train_images()
scipy.misc.toimage(scipy.misc.imresize(images[0,:,:] * -1 + 256, 10.))
```

## Software and Libraries

This project uses the following software and Python libraries:

* [Python](https://www.python.org/downloads/release/python-364/)
* [NumPy](http://www.numpy.org/)
* [scipy](https://www.scipy.org/)
* [matplotlib](https://matplotlib.org/)
