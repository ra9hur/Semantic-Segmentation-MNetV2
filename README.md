# Semantic-Segmentation-MNetV2
### Introduction
The objective of the project is to label the pixels of a road in images as either road/not-road by implementing a Fully Convolutional Network for semantic segmentation. This classification will help other systems in the car determine where the free space is. This technique could be extended to more classes like road, vehicle, bicycle and pedestrian.

In this implementation, MobileNet V2 is used as base feature extractor (encoder).

### Model Documentation

##### Approach
Semantic segmentation was implemented using MobileNet V1 and could be referred [here](https://github.com/ra9hur/SDC-P13-Semantic-Segmentation). MobileNet V1 had pre-trained 'imagenet' weight size of about (~ 70 MB). 

This implementation uses MobileNet V2. Pre-trained weight size is about (~ 9 MB) and this is significantly less when compared to MobileNet version 1. 

Weight files for keras's mobilenetv2 model can be downloaded [here](https://github.com/JonathanCMitchell/mobilenet_v2_keras/releases/).