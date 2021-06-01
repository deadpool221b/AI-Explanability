# AI-Explanability

## Overview
This is a ML model to predict that an instance(image) belongs to a certain class. We will be using InceptionV3, a pretained model in Keras library to predict the Dog as a labrador.

##
Step 1: Import the following libraries
* numpy
* skimage
* sklearn
* warnings
* copy

Step 2: Initialize the pretained Keras model InceptionV3

Step 3: Read and preprocess the image

Step 4: Predict class of Input Image.

## Explanation

* Extract superpixels and creates random pertubations of the image.
* Use ML classifier to predict classes of new generated images
* Compute distances between the original image and each of the perturbed images and compute weights of each perturbed image by using a kernel.
* Use perturbations, predictions and weights to fit an explainable model.

