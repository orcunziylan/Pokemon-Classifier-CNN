# Pokemon Classifier CNN

This repository contains code for a Pokémon image classification project. The goal is to build and train a Convolutional Neural Network (CNN) that can classify images of Pokémon. The dataset used for this project is available on Kaggle: [Pokemon Generation One Dataset](https://www.kaggle.com/thedagger/pokemon-generation-one).

## Overview

The project involves the following steps:

1. **Data Download and Preparation:** The code includes functions to download and prepare the dataset. The dataset is downloaded from Kaggle and then processed to remove duplicate and non-usable images. The following are some of the issues encountered in the dataset:
    
    - **Duplicate Images**
    
    <img width="339" alt="image" src="https://user-images.githubusercontent.com/55997117/165742007-e030a614-507c-4ec8-bfcd-f3ff382f6fe3.png">


    - **Wrong / Missing Labeled Images**
   
    <img width="610" alt="I'mage" src="https://user-images.githubusercontent.com/55997117/165742066-81046dac-7d74-47c9-8059-c3bd60d32f78.png">


    - **Weird / Unrelated Images**
   
    <img width="559" alt="image" src="https://user-images.githubusercontent.com/55997117/165742798-ca0fa09f-ded0-4660-ba1d-084d50d8c622.png">

3. **Data Augmentation:** Data augmentation is applied to increase the diversity of the training dataset. This helps in improving the model's performance by providing more variations of the same image.

4. **Model Architecture:** The code includes the architecture of the deep learning model used for image classification. The model consists of several convolutional layers followed by batch normalization, max-pooling, and dropout layers. The final layer uses softmax activation to predict the class probabilities.

5. **Training:** The model is trained using the prepared dataset. The training process involves calculating loss and accuracy metrics on both the training and testing datasets. The training progress is logged using TensorBoard.

6. **Evaluation:** The trained model is evaluated on the testing dataset to assess its accuracy and performance.

7. **Prediction:** The code also includes functions to predict the class labels of new Pokémon images using the trained model.

## Results

<img width="400" alt="image" src="https://user-images.githubusercontent.com/55997117/165743139-df0dd334-0a0e-43f8-973a-9d945fe88cba.png"><img width="400" alt="image" src="https://user-images.githubusercontent.com/55997117/165743165-e25a3758-78eb-42e1-9844-ea3d64d3b3e7.png">
