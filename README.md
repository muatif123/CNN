# Convolution Neural Network using Tensorflow and Keras

A Convolutional Neural Network (ConvNet/CNN) is a Deep Learning algorithm which can take in an input image, assign importance (learnable weights and biases) to various aspects/objects in the image and be able to differentiate one from the other. The pre-processing required in a ConvNet is much lower as compared to other classification algorithms. While in primitive methods filters are hand-engineered, with enough training, ConvNets have the ability to learn these filters/characteristics.
The architecture of a ConvNet is analogous to that of the connectivity pattern of Neurons in the Human Brain and was inspired by the organization of the Visual Cortex. Individual neurons respond to stimuli only in a restricted region of the visual field known as the Receptive Field. A collection of such fields overlap to cover the entire visual area.

Refer: https://towardsdatascience.com/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way-3bd2b1164a53 for full understanding of CNN

## About Tensorflow

TensorFlow is an end-to-end open source platform for machine learning
TensorFlow is an end-to-end open source platform for machine learning. It has a comprehensive, flexible ecosystem of tools, libraries, and community resources that lets researchers push the state-of-the-art in ML, and gives developers the ability to easily build and deploy ML-powered applications.

TensorFlow provides a collection of workflows with intuitive, high-level APIs for both beginners and experts to create machine learning models in numerous languages. Developers have the option to deploy models on a number of platforms such as on servers, in the cloud, on mobile and edge devices, in browsers, and on many other JavaScript platforms. This enables developers to go from model building and training to deployment much more easily.

Easy model building
Build and train ML models easily using intuitive high-level APIs like Keras with eager execution, which makes for immediate model iteration and easy debugging.

Robust ML production anywhere
Easily train and deploy models in the cloud, on-prem, in the browser, or on-device no matter what language you use.

Powerful experimentation for research
A simple and flexible architecture to take new ideas from concept to code, to state-of-the-art models, and to publication faster.

Refer: https://opensource.google/projects/tensorflow 

## About Keras

Keras is an open source deep learning framework for python. It has been developed by an artificial intelligence researcher at Google named Francois Chollet. Leading organizations like Google, Square, Netflix, Huawei and Uber are currently using Keras. This tutorial walks through the installation of Keras, basics of deep learning, Keras models, Keras layers, Keras modules and finally conclude with some real-time applications.
More on Keras : https://www.tutorialspoint.com/keras/index.htm


### About the uploaded files
Contains 3 Jupyter Notebook files which explain the working of tensorflow and keras on different datasets

1. ##### CNN MNIST Dataset : MNIST is an inbuilt image dataset for images classification of CNN using Tensorflow and Keras.  
2. ##### CNN CIFAR-10: CIFAR-10 is an inbuilt image dataset for images classification of CNN using tensorflow and Keras.
3. ##### CNN Real World Images: Generating model on real world images of body cells infected with the malaria disease and to predict using an image if it is parasitized or uninfected. The model is trained on huge dataset with training images of 12400 and test images of 1300 length. 
<br>
<br>
For better understanding of sequential model : https://keras.io/guides/sequential_model/
