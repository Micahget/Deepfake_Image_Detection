# Deepfake Image Detection

## Introduction
This project is a part of my research activity at the Marwadi University. The goal of this project is to detect deepfake images. 

Deepfake images are the images that are generated using deep learning techniques. These images are generated using Generative Adversarial Networks (GANs). The deepfake images are very difficult to detect using traditional image processing techniques. Therefore, in this project, I have used deep learning techniques to detect deepfake images.

## Dataset

The dataset used in this project is the [Deepfake Detection Challenge Dataset](https://www.kaggle.com/c/deepfake-detection-challenge/data). The dataset contains videos of real and deepfake faces. The dataset is divided into two parts: training and validation. 


## Model

I have used the [IncptionV3](https://keras.io/api/applications/inceptionv3/) model for detecting deepfake images. The InceptionV3 model is a pre-trained model that is trained on the ImageNet dataset. I have fine-tuned the InceptionV3 model on the Deepfake Detection Challenge Dataset.

Another model used is the [InceptionResNetV2](https://keras.io/api/applications/inceptionresnetv2/) model. The InceptionResNetV2 model is also a pre-trained model that is trained on the ImageNet dataset. I have fine-tuned the InceptionResNetV2 model on the Deepfake Detection Challenge Dataset.