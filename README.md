# Facial-Expression-Recognition
A deep learning model capable of recognizing emotions from facial expressions. You're using the CK+ (Extended Cohn-Kanade) dataset, which contains facial images depicting different emotions such as happiness, sadness, anger, surprise, fear, and disgust. 

## Data Loading and Preprocessing:
### You load the CK+ dataset, which consists of grayscale facial images labeled with corresponding emotion categories. Preprocessing steps include resizing images to a consistent size (e.g., 48x48 pixels), converting them to grayscale, and normalizing pixel values to the range [0, 1].

## Model Building:
### CNN Model: The project utilizes a CNN-based architecture for emotion recognition. The CNN model typically consists of convolutional layers followed by pooling layers for feature extraction, and fully connected layers for classification.
### ViT Model: In addition to CNNs, the project explores the use of Vision Transformer (ViT) models for the same task. ViT models employ self-attention mechanisms to capture global dependencies in images without using CNNs.

## Training:
### Both CNN and ViT models are trained using the preprocessed dataset. Training involves optimizing the model parameters using backpropagation and minimizing a suitable loss function such as categorical cross-entropy.

## Evaluation:
### The trained models are evaluated using a separate test dataset to assess their performance in terms of accuracy and other relevant metrics.
### CNN Accuracy: 97%
### ViT Accuracy: 95%
