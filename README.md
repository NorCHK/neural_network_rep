# neural_network_rep
# Emotion Recognition using MFCC and Neural Networks 

## Description

This project aims to recognize emotions from Arabic audio data using a neural network. The model is trained with Mel-frequency cepstral coefficients (MFCCs) extracted from audio clips. The goal of this task is to classify the audio into three emotion categories:

- **0**: Sad
- **1**: Neutral
- **2**: Happy

Currently, the model achieves an accuracy of around 40%, which is suboptimal. 

## Features

- **Neural Network**: The model is implemented using basic neural network layers with ReLU activation functions for hidden layers and Softmax for the output layer.
- **Loss Function**: The sparse categorical cross-entropy loss function is used to calculate the model's loss and update the weights during training.
- **Performance**: As of now, the model achieves an accuracy of approximately 40%. Further improvements are planned to optimize the model’s performance.

## Installation

To run this project, you will need to install the following Python libraries:

_ numpy
_ matplotlib
_ tensorflow
_ scikit-learn
_ pandas


### Clone the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/NorCHK/neural_network_rep.git

