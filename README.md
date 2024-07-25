# Emotion Detection using CNN and FER-2013 Dataset

This project focuses on developing an emotion detection system using Convolutional Neural Networks (CNNs) trained on the FER-2013 dataset. The FER-2013 dataset, which contains 35,887 grayscale, 48x48 pixel images of faces, each labeled with one of seven emotions (anger, disgust, fear, happiness, sadness, surprise, and neutral), is used to train the CNN model to accurately classify emotions from facial expressions. The model architecture, data preprocessing techniques, and evaluation metrics are meticulously designed to achieve high accuracy in emotion recognition.

Trained models:

1. Built a CNN architecture from Scratch
2. Built a CNN appliying Transfer Learning usign VGG16 CNN Arch.
3. Lastly Built Model using Resnet50-V2 and Achieved a approx of 60% accuracy.

## Building a CNN Applying Transfer Learning Using VGG16

* Project Focus: Application of transfer learning to build a Convolutional Neural Network (CNN) using the VGG16 architecture.
* Pre-trained Model: Utilizes VGG16, known for its deep layers and high accuracy on image classification tasks.
* Transfer Learning Approach: Leverages pre-trained weights from VGG16 for efficient feature extraction. Later fine-tuned the top layers of the network to adapt to the specific task.
* Benefits: Reduces training time. Improves model performance by building on the learned features of VGG16.
* Process: Integrate VGG16 as the base model. Modify the network architecture to suit the new dataset. Train the model while retaining the learned weights of the convolutional base.
* Objective: Demonstrate the efficiency and effectiveness of transfer learning in building robust CNN models for various applications.

## Building a CNN from Scratch

This project involves developing a Convolutional Neural Network (CNN) from scratch for image classification. The custom architecture is designed to effectively learn and classify images using multiple convolutional, activation, normalization, pooling, and dropout layers.

### CNN Architecture Overview
  This custom Convolutional Neural Network (CNN) is designed for image classification with the following key components:
* Convolutional Layers: 6 convolutional layers to extract features.
* Activation Layers: ReLU activation functions after each convolution.
* Batch Normalization Layers: 3 layers to stabilize and speed up training.
* Pooling Layers: 3 MaxPooling2D layers to reduce spatial dimensions.
* Dropout Layers: 3 dropout layers to prevent overfitting.
* Fully Connected Layers: 2 dense layers, including the output layer.


## Emotion Detection Using ResNet and FER-2013 Dataset
This project focuses on emotion detection using the Residual Network (ResNet) architecture with the FER-2013 dataset. Key aspects of the project include:

* Architecture: Utilizes ResNet, which features residual learning to solve the vanishing gradient problem, allowing the better training of very deep networks.
* Transfer Learning: Leverages pre-trained ResNet models and fine-tunes them for the specific task of emotion detection.
* Objective: Achieved high accuracy in emotion recognition by leveraging the robust architecture of ResNet
This project highlights the effectiveness of ResNet in deep learning tasks and its application in affective computing.

### ResNet performed well w.r.t CNN built from scratch and VGG16 model, also achieved a good F1-score respectively.

#### If you want the full code for these projects, please contact me on [LinkedIn](https://www.linkedin.com/in/ansh-kapoor-a153a8222/).
