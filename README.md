# ML-NEURAL_NETS

Implemented Neural Nets using the ToyotaCorolla Data

The data has 1436 records and details on 38 attributes, including Price, Age, KM, HP, and other specifications

The goal is to predict the price of a used Toyota Corolla based on its specifications using a multilayer neural network. Select appropriate predictor variables

The data was split 75%  for training a multilayer neural network and 25% to validate the network performance (“rprop+” in the neuralnet package was used)

The RMS error for the training data and the validation data was recorded and the process was repeated for different threshold values of 1, 0.1, 0.05, 0.01, 0.005, 0.001, and 0.0001
The data set was explored and  RMS error (or Sum of Squares Error) values were compared when the threshold increases/decreases for both validation and testing data

An experiment was conducted to assess the effect of changing the number of hidden layer nodes (default 1), e.g., 1,2,4,8 

Also a similar experiment to assess the effect of changing the number of layers from 1 to 2 in the network

The effect of gradient descent step size (learningrate) on the training process and the network performance was studied and concluded
