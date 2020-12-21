
# Data Scientist Nanodegree: Capstone Project


![dog_breed_main_pic](images/dog_breed_main_pic.jpg)

The purpose of this project is to use a convolutional neural network (CNN) to predict dog breeds. The pipeline is the evaluation of an image as a dog or a human, then a prediction of which dog breed the dog is, or which dog breed the human most resembles. 

How I proceeded exactly and what results I achieved can be read in my blog post: (LINK)


## Table of Contents
1. [Introduction](#introduction)
2. [Software Requirements](#software_requirements)
3. [Folder Structure](#folder_structure)
4. [Getting Started](#getting_started)

XX. [Authors](#authors)
XX. [Project Motivation](#motivation)
XX. [Acknowledgements](#acknowledgement)




<a name="introduction"></a>

## Introduction

In the course of this nanodegree from Udacity, as part of the Capstone project, I created a pipeline that can be used in a web or mobile app to process real images taken by users. Based on a picture of a dog, the algorithm I created can make an assessment about the dog breed. If supplied an image of a human, the code will identify the resembling dog breed.

<a name="software_requirements"></a>

## Software Requirements

Required libraries:

+ sklearn==0.23.2
+ keras==2.4.3
+ tensorflow==2.4.0
+ numpy==1.19.2
+ pandas==1.1.3
+ matplotlib==3.0.3
+ opencv==3.0.3
+ tqdm==4.52.0

Please run ```pip install -r requirements.txt```



<a name="folder_structure"></a>

## Folder Structure

```
C:.
│   dog_app.ipynb
│   extract_bottleneck_features.py
│   README.md
│   requirements.txt
│
├───bottleneck_features
├───data
│   ├───dog_images
│   └───lfw
├───haarcascades
│       haarcascade_frontalface_alt.xml
│
├───images
│       American_water_spaniel_00648.jpg
│       border_collie.jpg
│       Brittany_02625.jpg
│       Curly-coated_retriever_03896.jpg
│       dog_breed_main_pic.jpg
│       german_shepherd_dog.jpg
│       great_dane.jpg
│       Labrador_retriever_06449.jpg
│       Labrador_retriever_06455.jpg
│       Labrador_retriever_06457.jpg
│       man.jpg
│       sample_cnn.png
│       sample_dog_output.png
│       sample_human_2.png
│       sample_human_output.png
│       Welsh_springer_spaniel_08203.jpg
│       woman1.jpg
│       woman2.jpg
│
└───saved_models
```


<a name="getting_started"></a>

## Getting Started

1. Make sure Python 3 is installed
2. Clone the repository and navigate to the project's root directory in the terminal
3. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip). Unzip the folder and place the three files (test, train and valid) in the cloned repository in the folder ```data/dog_images```. If one of these folders does not yet exist, please create it manually. 
4. Download the [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip). Unzip the folder and place it in the cloned repository in the folder ```data/lfw```. If one of these folders does not yet exist, please create it manually. 
5. Download the VGG-16 and InceptionV3 bottleneck features and place them in the cloned repository in the folder ```bottleneck_features```. If this folder does not yet exist, please create it manually. 
6. Start the notebook ```dog_app.ipynb```.





<a name="authors"></a>

## Authors

+ [Michael Fuchs](https://github.com/MFuchs1989)

<a name="motivation"></a>

## Project Motivation: 

Udacity has given students the freedom to choose the area in which they would like to complete their capstone project. Possible technical fields would have been:

+ [Robot Motion Planning](https://docs.google.com/document/d/1ZFCH6jS3A5At7_v5IUM5OpAXJYiutFuSIjTzV_E-vdE/pub)
+ [Healthcare](https://docs.google.com/document/d/1WzurKKa9AX2DnOH7KiB38mvozdOSemfkGpex8hdTy8c/pub)
+ [Computer Vision](https://docs.google.com/document/d/1y-XfjkPFgUQxFIQ9bBncUSjs4HOf5E-45FrLYNBsZb4/pub)
+ [Education](https://docs.google.com/document/d/1vjerjRQnWs1kLbZagDYT6rNqiwAG23Yj45oUY88IAxI/pub)
+ [Investment and Trading](https://docs.google.com/document/d/1ycGeb1QYKATG6jvz74SAMqxrlek9Ed4RYrzWNhWS-0Q/pub)

As I am personally very interested in Deep Learning and have already completed my Nanodegree in Computer Vision via Udacity, I found it exciting to complete my capstone project in this area as well. 
So I choose to use Convolutional Neural Networks to Identify Dog Breeds.

<a name="acknowledgement"></a>

## Acknowledgements

I thank [Udacity](https://www.udacity.com/) for providing this challenge and learning experience. 