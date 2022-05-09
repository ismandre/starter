
# ./starter

This page is primarily intended for me to keep track of and organize my GitHub repositories into meaningful units. Somewhere along the way when implementing this idea I thought that this page could serve me well both to organize not only GitHub repos but any other college and non-college related work and projects and to show someone else my areas of interest along with some demo apps. Particularly, my area of interest is application of machine learning and deep learning concepts and models in the field of computer vision. Having my bachelor thesis done in the given field. In my free time I like learning new stuff about Android and iOS apps development tools. Having that in my mind, this page will be organized into sections which are not yet defined but will be as I progress with this idea. 


# Table of contents
1. [My Respositories](#my-repositories)
	1. [College](#college)
	2. [Machine Learning](#machine-learning)
	3. [Mobile](#mobile)
		1. [Android](#android)
		2. [iOS](#ios)
	4. [Tasks and Assignments](#tasks-and-assignments)
	5. [Web](#web)
		1. [Spring Boot](#spring-boot) 
2. [Computer  Vision Roadmap](#computer-vision-roadmap)
3. [IELTS Preparation](#IELTS-preparation)
4. [Orchestration Using Anisble and Virtual Machines](#orchestration)


# My Repositories<a name="my-repositories"></a>

## College<a name="college"></a>

- [Introduction to Data Science: Project](https://github.com/ismandre/uzop-heart-disease)
- [Project Computing](https://github.com/ismandre/Projekt-R)
- [Seminar 1](https://github.com/ismandre/seminar-1)
- [Software Engineering: Project](https://github.com/ismandre/Programsko-Inzenjerstvo-Projekt)
- [Statistical Data Analysis: Project](https://github.com/ismandre/Statisticka-Analiza-Podataka-Projekt)

## Machine Learning<a name="machine-learning"></a>

- [Deep Learning Specialization Course](https://github.com/ismandre/deep-learning-specialization)

## Mobile<a name="mobile"></a> 

### Android<a name="android"></a>

- [Infinum Android Academy](https://github.com/ismandre/isa-shows-app-dnaram)
- [Service and application development for Android OS by FIVE](https://github.com/ismandre/android-vjestina-tmdb)

### iOS<a name="ios"></a>

- [Service and application development for iOS by FIVE ](https://github.com/ismandre/iOS-Vjestina-QuizApp)
- [SofaScore iOS Course](https://github.com/ismandre/sofascore-ios-course)

## Tasks and Assignments<a name="tasks-and-assignments"></a>

- [ecx.io assignment for student internship](https://github.com/ismandre/ecxio-DemoApp)
- [Global Logic assignment for Java Academy](https://github.com/ismandre/global-logic-assignment)

## Web<a name="web"></a>

### Spring Boot<a name="spring-boot"></a>

- [Agency 04 Summer School](https://github.com/ismandre/ag04-pizzaApp)


# Computer Vision Roadmap<a name="computer-vision-roadmap"></a>

## Roadmap to Computer Vision
For more details here is the [link](https://resources.experfy.com/ai-ml/roadmap-to-computer-vision/?ref=morioh.com&utm_source=morioh.com).

## How to Become a Computer Vision Engineer in 2022?

For more details here is the [link](https://www.projectpro.io/article/computer-vision-engineer/469).

## Here's your Learning Path to Master Computer Vision in 2020

For more details here is the [link](https://www.analyticsvidhya.com/blog/2020/01/computer-vision-learning-path-2020/).

## Complete Deep Learning & Computer Vision Roadmap for Beginners

For more details here is the [link](https://www.youtube.com/watch?v=OSLC-bx_kik).

## Roadmap for Conquering Computer Vision

For more details here is the [link](https://towardsdatascience.com/roadmap-for-conquering-computer-vision-213695472ad0).

## Getting Started: Computer Vision Roadmap

For more details here is the [link](https://www.kaggle.com/getting-started/158267).

## Deep Learning Book

For more details here is the [link](https://www.deeplearningbook.org/).


# IELTS preparation<a name="IELTS-preparation"></a>

## IELTS Full Course in 10 hours - 2022

For more details here is the [link](https://www.youtube.com/watch?v=Jzps8q2es7c).

### Introduction to IELTS

### Listening: Structure

### Listening: Sections Explained

### Listening: Introduction to Accents

### Listening: Form Completion

### Listening: Table Completion

### Listening: Sentence Completion

### Listening: Multiple Choice Questions

### Listening: Short Answers

### Listening: Map Labeling

### Listening: Flow-Chart Completion


# Orchestration using Ansible and Virtual Machines<a name="orchestration"></a>

## How to Set Up SSH Keys on Ubuntu 18.04

For more details click [here](https://www.digitalocean.com/community/tutorials/how-to-set-up-ssh-keys-on-ubuntu-1804).

## SSH into VirtualBox VM [Step-by-Step]

For more details click [here](https://www.golinuxcloud.com/ssh-into-virtualbox-vm/).

## How to connect to VirtualBox via SSH

For more details click [here](https://linuxconfig.org/unable-to-ssh-into-virtualbox-guest-machine).






# Introduction to Deep Learning (MIT 6.S191)

> MIT's introductory course on deep learning methods with applications in art, computer vision, robotics, medicine, language and more!

## Lecture 1: Intro to Deep Learning

## Lecture 2: Deep Sequence Modeling

  
## Lecture 3: Deep Computer Vision

> **NOTE**: This section is based on the video material which is accessible through the given [link](https://www.youtube.com/watch?v=uapdILWYTzE&list=PLtBw6njQRU-rwp5__7C0oIVt26ZgjG9NI&index=3).

When speaking about vision generally we can agree that the ability to see entails following set of activites:
- to discover from images 
	- **what** is present in the image
	- **where** are objects located in the image
	- what **actions** are taking place
	- and/or **predict** and **anticipate** events in the image/world	

![Computer vision tasks applied to image](https://i.imgur.com/zcFKYx9.png)

The rise and impact of computer vision can be seen in various fields such as robotics, mobile computing, biology and medicine, autonomous driving and accessibility and this will serve as a motivation when dealing with the technical part of deep learning applied to computer vision. 

To start dealing with the computer vision problems solving approach based on deep learning it is important to ask ourselves following questions:
- How can we build a computer *to see*?
- How can we build a computer to process an image in a way it can understand?
- How computer perceives an image when dealing with these kinds of tasks?

We will firstly deal with the third question from those listed above. When dealing with images, computer only *sees* data structure consisting of numbers being that some kind of arrays, lists or matrices. It would be more precise to say that computer **operates** with those number rather than saying that computer sees them.  

In the case of a gray-scale image it is being represented as a 2D matrix of a pixel values. Every pixel value is represented as an integer ranging from 0 to 255. It is important to notice that $$256=2^8$$ so it is clear that every pixel value is presented using 8 bits and given those 8 bits the closer the pixel value is to 0 the darker the pixel will be and vice versa with the upper value of 255.

In the case of an RGB image where these three letters stand for the three primary colors of red, green and blue the image representation is similar. But in this case we have three matrices - one for each of the color channel making this structure a 3D matrix. Still, each pixel value for each of the matrices will denoted the intensity of that color for the given location of the pixel.

![Image representation as pixel values](https://i.imgur.com/hY5sTQa.png)

Now that we know how images are stored in a computer and how computer will perceive them for the future use and pixel values manipulation (being that 2D gray-scale image or a 3D RGB image) it is time to start defining concrete problems which will tackle with later in this section.

Tasks in computer vision and machine learning in general can roughly be divided to regression problems and classification problems. Regression deals with the tasks in which the output variable (often denoted as $y$) takes a continuous value from the set of a real numbers, $\mathbb{R}$. On the other hand, classification tasks include problems in which the output variable takes a value (often called *class*) from a discrete set of values such as a set of whole numbers, $\mathbb{Z}$. It is not rare that in classification problems the probability of the example (i.e. image) belonging to each of the classes is being calculated. 

When dealing with the classification tasks for computer vision it is reasonably clever to start by decomposing the input image to its high level features and then based on the observed features make a prediction about which of the classes the input image is generated from. For example, let's say that we are given an image of a human face. We will know that the given image contains a human face in it because we detected high level features such as nose, eyes and mouth and all of them being in right places relative to each other. Same idea can be used for detecting cars, houses and any other object composable to its high level features.   

Previously described idea seems fairly useful: 
1. decompose the input image to its high level features
2. compare detected features to the ones contained by the target classes
3. choose a target class whose high level features overlap the most with the input image

The problem with this approach is that defining and extracting quality and representative features is not an easy task to do. It has been shown that people are not good at extracting quality high level features that would be robust to input images with wide range of viewpoint and scale variations, deformations, occlusions and illumination conditions. 

![Different image variations](https://i.imgur.com/gHL2NPH.png)

So it seems that humans and hand-crafted feature extraction is not a clever way to solve this problem. Can we come up with an approach in which high level features will be learned based on a huge amount of images starting from low level features such as lines, edges and dark spots going to mid level features such as eyes, ears and nose all the way to the high level features such as facial structure? And the answer is: yes! Learning a hierarchy of features directly from the data instead of hand engineering can be done using neural networks.

One of the main reasons for applying deep learning models is that it is sparing us from the tedious task of coming up with a useful set of hand crafted features being that ones extracted from images, text of audio recordings. In previous lectures we defined the structure of a fully connected neural network so let's start explaining this kind of approach using that model.

As we said earlier, images are being represented as a 2D or 3D matrix of pixel values. This can cause problems when feeding the neural network with given values since neural network receive a vector of value to as its input. One way of solving this problem would be to flatten our image so that it is no longer 2D or 2D but 1D and the length of the given vector would be equal to the number of pixels representing an image. For example, let's say that we are dealing with an RGB image with height dimension being set to $height$, width dimension being set to $width$ then the resulting vector would have $width * height * 3$ values and it would be reshaped as an 1D input suitable for a neural network. However, this brings up a new set of implications and/or problems:
- neuron in the hidden layer has to be connected to all neurons (pixel values) from the input layer
- spatial information about relative position of a one pixel to its neighboring pixel is being lost
- following the first implication, there is going to be a huge number of parameters (depending also on the number of hidden layers).

Of all mentioned implications, the second one seems to be quite a problem. Pixels which have previously been close to each other may now be scattered far away and those which have previously been far away from each other can now become neighbors thanks to the flattening process. Obviously, we want to avoid this from happening. So, the conclusion is that neural networks will not be a way to go for feature extraction part of the problem.

To preserve spatial structure of the image we will deal with it in its original shape as an 2D array of pixel values. Now, since we cannot feed the neural network in this way as we already stated earlier, we will try to come up with a different approach. The idea is actually quite simple. We will connect parts of the image (called *patches*) to the neurons in the hidden layer. So that implicates that some neuron from the hidden layer *sees* only pixel value from the given patch or a given region of the input. This solves problems stated above - this way number of parameters is greatly reduced and spatial structure of the image is preserved. 

![Spatial preserving approach for feature extraction](https://i.imgur.com/VWclgEY.png) 
 
Let's expand this idea little bit. As we said earlier we will define a *patch* or a region of an image and connect pixel value from the defined regions to the neuron from the hidden layer and will slide window across the input image to connect *patches* of the input image to the neurons from the hidden layer. This sliding operation and extraction of features is called **convolution**. General steps used are as followed:
1. apply a set of weights - a *filter* - to extract local features
2. use multiple filters to extract different features
3. spatially share parameters of each filter
 
This generic set of steps will be explained using *X or X* example. So, the goal is to identify the letter X even in images when the letter is being shifted, shrunk, rotated and deformed in any other way but still resembling to its original shape. 

![X or X problem](https://i.imgur.com/QQky2Bf.png)
   
In our simplified example, we will two different pixel values:
- -1: representing black pixels
- 1: representing white pixels.
 
The naive approach would take pixel from the original image and pixel from the deformed image and compare those two values and repeat that process for each of the images' pixels. At the end of the algorithm we would find ourselves with some kind of distance metric between those two images and we would make a decision based on some predefined threshold for the acceptable distance/similarity. But, the problem with this approach is that it is not robust enough. We will find ourselves detecting images of X which are almost identical but fail to detect rotated and shifted images since those will differ in almost every pixel we try to compare with the original image. 

We will try to resolve to some more robust idea. Let's recollect that idea of extracting high level features. We will do exactly that. Images will be compared not pixel by pixel but image region by image region and if similar features are found on the approximately exact locations then we can assume that it is the case that both images contain the letter X.

  ![Compare images region by region](https://i.imgur.com/WmeQzSU.png)

How will we extract those features? To extract valuable features from the input image we will define so called *filters*. Filters are actually "mini images" which will create a *mask* for parts of an image that will be used to extract feature. For example, let's say that we want to extract crossing part of the letter X. In this case we could define filter like this:

$$filter = \begin{bmatrix}  
1 & -1 & -1\\  
-1 & 1 & -1 \\
-1 & -1 & 1 
\end{bmatrix}$$ 

and now we we can perform an elementwise multiplication between this filter and a region of image having the same dimension as a filter and sum over every value in the result matrix and we will end up with some scalar value. The important point to notice here is that the higher the value of the dot product operation the higher resemblence between that part of the image and feature wanting to be extracted be the filter.

![Peforming convolution](https://i.imgur.com/j28f0DE.png)

  
  
