# Comp4901J Deep Learning In Computer Vision - Assignment2

The course website: https://course.cse.ust.hk/comp4901j/

Fully-Connected Nets, Batch Normalization, Dropout, Convolutional Nets

In this assignment you will practice writing backpropagation code, and training Neural Networks and Convolutional Neural Networks. The goals of this assignment are as follows:

understand Neural Networks and how they are arranged in layered architectures
understand and be able to implement (vectorized) backpropagation
implement various update rules used to optimize Neural Networks
implement batch normalization for training deep networks
implement dropout to regularize networks
effectively cross-validate and find the best hyperparameters for Neural Network architecture
understand the architecture of Convolutional Neural Networks and gain experience with training these models on data

Important note from YY: we have updated the skeleton codes, please download it again if you downloaded it before 5 Oct 2017.

Download data: Once you have the starter code, you will need to download the CIFAR-10 dataset. Run the following from the assignment2 directory:

cd cs231n/datasets folder and click get_datasets.py to run the Python code to download the data.
Submitting your work:
Whether you work on the assignment locally or in the lab, once you are done working run the Python code collectSubmission.py; this will produce a file called assignment2.7z. Upload this file to CASS. You can find CASS instruction of uploading your submission here.

Q1: Fully-connected Neural Network (25 points)
The IPython notebook FullyConnectedNets.ipynb will introduce you to our modular layer design, and then use those layers to implement fully-connected networks of arbitrary depth. To optimize these models you will implement several popular update rules.

Q2: Batch Normalization (25 points)
In the IPython notebook BatchNormalization.ipynb you will implement batch normalization, and use it to train deep fully-connected networks.

Q3: Dropout (10 points)
The IPython notebook Dropout.ipynb will help you implement Dropout and explore its effects on model generalization.

Q4: Convolutional Networks (30 points)
In the IPython Notebook ConvolutionalNetworks.ipynb you will implement several new layers that are commonly used in convolutional networks.

Q5: PyTorch / TensorFlow on CIFAR-10 (10 points)
For this last part, you will be working in either TensorFlow or PyTorch, two popular and powerful deep learning frameworks. You only need to complete ONE of these two notebooks. You do NOT need to do both, but a very small amount of extra credit will be awarded to those who do.

Note from CK: please complete only the Tensorflow notebook for HKUST version of the assignmenet because our WinPython package only supports Tensorflow.
Open up either PyTorch.ipynb or TensorFlow.ipynb. There, you will learn how the framework works, culminating in training a convolutional network of your own design on CIFAR-10 to get the best performance you can.

Q5: Do something extra! (up to +10 points)
In the process of training your network, you should feel free to implement anything that you want to get better performance. You can modify the solver, implement additional layers, use different types of regularization, use an ensemble of models, or anything else that comes to mind. If you implement these or other ideas not covered in the assignment then you will be awarded some bonus points.
