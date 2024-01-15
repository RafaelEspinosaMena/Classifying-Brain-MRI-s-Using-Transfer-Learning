# Classifying Brain MRI's Using Transfer Learning and TensorFlow

## Overview 

This project is to classify images of brain MRI's into two categories: tumor or no tumor. I used the pre-trained InceptionResnetV2 network from TensorFlow and then add on three dense layers that will be trained on this specific dataset.

## Data Augmentation

I designed a custom data augmentation pipeline where the images are stretched, compressed, rotated and their brightness' changed in order to create more, synthetic, images for the network to train on. 

## Results

The network achieved a test accuracy of 94%. This is remarkable as in general, human radiologists achieve a similar accuracy when classifying MRI's themselves. 
