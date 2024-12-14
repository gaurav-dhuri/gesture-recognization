
# Project Name
Gesture Recognition Project using deep learning


## General Information
We need to develop a cool feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote.

For analysing videos using neural networks, two types of architectures are used commonly. One is the standard CNN + RNN architecture in which you pass the images of a video through a CNN which extracts a feature vector for each image, and then pass the sequence of these feature vectors through an RNN. This is something you are already familiar with (in theory). 

The other popular architecture used to process videos is a natural extension of CNNs - a 3D convolutional network. In this project, you will try both these architectures

## Conclusions
The Model built with Time distributed Conv2D and ConvLSTM2D gave better results compared to all the other Conv3D models and also the model has very least number of parameters compared to other models.
As per the above experiment we have decided to go with CNN-RNN Transferred Learning (GRU) model because it gives the best accuracy as compared to any other model that have been trained.



## Libraries Used
- Keras 
- numpy 
- matplotlib 
- skimage



## Contact
Created by Gaurav Dhuri


Developed as part of the Advanced Regression Module required for Post Graduate Diploma in Machine Learning and AI - IIIT,Bangalore.
