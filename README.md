# Binary-Classification-using-PyTorch
This repository contains a PyTorch implementation of a binary classification model using convolutional neural networks (CNNs).The model is designed to classify input data into one of two classes-0,1 based on learned features extracted through convolutional layers. 

# Project Structure
1. Initialize a dataset
2. Normalizing
3. Architecture of CNN:
   Maxpooling layer,
   Flatten layer,
   Fully connected layer,
   Activation functions: ReLU, Sigmoid;
   Loss function: Binary Cross Entropy Loss;
   Optimizer: Adam
4. Training loop
5. Calculating the loss value

# Output
The output of model(X_train[:8]) provides the predicted probabilities for each input sample in X_train[:8].
These probabilities represent the model's confidence in assigning each sample to the positive class (class 1) in the binary classification problem.
