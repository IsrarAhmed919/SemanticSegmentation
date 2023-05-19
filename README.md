# Image Segmenation
## Contents
1. [Introduction](#introduction)
2. [DataSet](#DataSet)
3. [CNN Architectures](#CNNArchitectures)
4. [Results](#Results)
6. [Authors](#authors)
 
 ## Introduction

Welcome to the Image Segmentation GitHub Repository! This repository provides a comprehensive exploration of image segmentation techniques, focusing on UNet combined with VGG and ResNet encoder backbones. We evaluate and compare the performance of these models on a 12-class dataset, measuring segmentation accuracy using metrics such as the Jaccard index. You'll find implementation code, training scripts, and pre-trained models to experiment with image segmentation on your own datasets. Join us in unlocking the power of image segmentation with UNet, VGG, and ResNet.

## DataSet
For this project we have used a cityescape dataset with 12 classes, you can use your own dataset with specified annotations for class categories and arousal and valance values.

## CNN Architectures

In this project, we utilized two popular CNN architectures as baselines for our model: ResNet and EfficientNetB0. ResNet is a deep residual neural network that has shown excellent performance in image classification tasks. It uses skip connections to allow information to pass through layers without being altered, thus enabling the network to learn more complex features. EfficientNetB0, on the other hand, is a lightweight and scalable CNN architecture that has been optimized for both accuracy and computational efficiency. It uses a combination of convolutional layers, squeeze-and-excitation blocks, and depthwise separable convolutions to extract features from images while minimizing the number of parameters and computations required. Both ResNet and EfficientNetB0 have been widely used in various computer vision applications, and we chose them as our baselines due to their proven performance in image classification tasks.

## Results
In this project, we utilize two popular CNN architectures as encoder backbones for image segmentation: VGG and ResNet. VGG is a deep and homogeneous architecture known for its exceptional performance in various computer vision tasks. It consists of multiple convolutional layers followed by max-pooling layers, resulting in progressively increasing receptive fields. This architecture enables VGG to capture rich and hierarchical features from input images.

On the other hand, ResNet stands out for its innovative use of skip connections, which address the vanishing gradient problem encountered in deep networks. By introducing residual connections, ResNet allows gradients to flow more efficiently during training, facilitating the learning of deeper and more expressive representations. The skip connections also enable the reuse of features from earlier layers, preserving fine details and enhancing the model's ability to capture complex structures.

Both VGG and ResNet offer unique advantages in the context of image segmentation. VGG's deep and homogeneous architecture enables it to capture intricate details, while ResNet's skip connections enhance feature propagation and enable better handling of complex structures. It is important to note that if trained for a longer duration, both architectures have the potential to further improve their performance, as the models can learn more intricate and discriminative representations. By incorporating these CNN architectures into the UNet framework, we leverage their respective strengths to achieve accurate and robust image segmentation results.

## Authors
Israr Ahmed <iahmed.msds22seecs@seecs.edu.pk>
