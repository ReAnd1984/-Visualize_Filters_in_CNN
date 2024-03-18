# Visualize Filters in CNN

![Logo](https://camo.githubusercontent.com/3225433dd177ce8d8255c760ab7aefbdba83107545b62d17f4459cde05ecedd5/68747470733a2f2f696d672e736869656c64732e696f2f707970692f707976657273696f6e732f74662d6167656e7473)

This notebook showcases the visualization of filters in Convolutional Neural Networks (CNNs), aiming to understand the activation patterns of specific filters within chosen layers of the network.

## Overview 
In this notebook, we leverage a pre-trained ResNet50V2 model with weights from the ImageNet dataset. Our goal is to gain insights into the inner workings of the network by visualizing the activation of filters in two specific layers: conv2_block1_1_conv and conv5_block3_3_conv.

To achieve this, we follow these steps:

__• Model Setup:__ Import the ResNet50V2 model and extract the desired layers for visualization.

__• Gradient Ascent:__ Implement gradient ascent to optimize an input image, maximizing the activation of a specific filter in the chosen layer.

__• Visualization:__ Visualize the activation of individual filters by generating images that highlight their responses.

__• Composite Images:__  Construct composite images containing multiple filters to observe their collective behavior and discern any discernible patterns.

Through this process, we aim to gain deeper insights into the features learned by the CNN filters and their role in processing images.
