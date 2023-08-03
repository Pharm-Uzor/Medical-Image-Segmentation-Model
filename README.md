# Medical-Image-Segmentation-Model

## Overview
This repository contains code and data for the segmentation of ultra-sound images of benign breast tumor images. The goal of image segmentation is to divide an input image into meaningful segments or regions, making it easier to analyze and understand the content within the image.

## Dataset
The dataset used for this task is the "Benign tumor images," which includes a collection of ultra-sound labeled with corresponding segment masks. 

## Model Architecture
The image segmentation task is accomplished using a U-Net architecture. U-Net is a convolutional neural network (CNN) that has shown promising results in various image segmentation tasks. The U-Net architecture consists of an encoder path that captures image features and a decoder path that upsamples the features to generate segmentation masks.
The final model is 30 layers deep and includes dropout layers for regularization.

## Code Organization
- 'benign tumor images': Contains the dataset used for training and evaluation.
- 'benign-breast-tumor-image-segmentation-v2.ipynb': Script for training the U-Net model on the dataset.

## Results
The model's performance on the test set will be displayed, including metrics such as Jaccard Coefficent and Mean IoU

## Acknowledgments
I would like to acknowledge Saba Hesaraki for providing the data used in this project.

## Contact
For any inquiries or issues, please contact uzoigodo@gmail.com.
