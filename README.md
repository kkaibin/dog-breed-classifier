# Dog Breed Classifier

## Table of contents
1. [Introduction](#Introduction)
2. [How to run](#Howtorun)
    1. [Requirements](#Requirements)
    2. [Instructions](#Instructions)
3. [Results](#Results)
    1. [Model Accuracy](#ModelAccuracy)
    2. [Classification](#Classification)
4. [Acknowledgement](#Acknowledgement)

<a name="Introduction"></a>
## Introduction

### Objective:
  We would like to train a model using CNN that categorizes dogs, humans, or any species into their similiar dog breeds. 

### Overview:
  There is a detector that detects whether the input picture contains a dog or human. The human detector employs one of OpenCV's pre-trained face detector, [Haar feature-based cascade classifiers](http://docs.opencv.org/trunk/d7/d8b/tutorial_py_face_detection.html), while the dog detector employs a pre-trained ResNet-50 model (weights trained on ImageNet).\
  \
  As for the dog breed classifier, two models are trained from a labled dog breed dataset, one model built from scratch and the other built from the pre-trained VGG-16 model.

<a name="Howtorun"></a>
## How to run

<a name="Requirements"></a>
### 1. Requirements

Python 3\
Libraries: SKlearn, keras, numpy, glob, cv2, random, tqdm, PIL, matplotlib.




<a name="Instructions"></a>
### 2. Instructions

  1.	Download the dataset of classified [dog images](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip) and the dataset of [humans](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip).\
  2.  Download the pretrained model, [Haar feature-based cascade classifiers](https://github.com/opencv/opencv/tree/master/data/haarcascades), and the [VGG-16 bottleneck features](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz).\
  3.  The code can run using google colab. (File paths need to be modified.)\

<a name="Results"></a>
## Results

<a name="ModelAccuracy"></a>
### 1. Model Accuracy


<a name="Classification"></a>
### 2. Classification


<a name="Acknowledgement"></a>
### Acknowledgement
Thanks to Udacity for the dataset, template, and training.
