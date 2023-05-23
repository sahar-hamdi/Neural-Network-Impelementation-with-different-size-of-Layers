# Neural-Network-Impelementation-with-different-size-of-Layers

in this repo I impelemented Neural Network from Scratch using python and I trained this model using differnt numbers for hidden layers
and Impelemented it using MNIST dataset

1. I Loaded MNIST dataset.
2. I Standardized your dataset
3. I Divided data into training and test.
4. I Applyed one hot vector for labels (meaning the value is 1 in the correct class and 0 in the
rest, there will be 10 classes so a vector of 10).
5. I Implemented a dynamic Neural Network from scratch.
 I Initialized the weights of the layers with random values.
 I Used equations to calculate the output for all the forward passes.
 I Used MSE as error function (between the one hot vector and the prediction
vector of the NN).
 I Applyed back propagation to update the weights.

Note:
- I Saved the output values in each layer as I will need them for the back propagation.
- I used Sigmoid as my Acctivation Function
An example for NN with 2 layers: input hidden layer 1 hidden layer 1 output 
output layer  output.
6. Function of neural network follows this format:
NN (x, y, num_of_layers, size_of_layers)
Example: NN(X, y, 2, [20, 10])
where 20 is the size of the hidden layer and 10 is the size of the output layer
Size of layer means number of neuron at this layer.
7. Tested code with the following architectures and report your different accuracies for
each case from the following:
1- I Built NN with only 2 layers => 1 hidden layer and 1 output layer
2- I Built NN with 3 layers=> 2 hidden layers
Where # of neurons in first layer < # of neurons in second layer and 1 output layer
3- I Built NN with 3 layers=> 2 hidden layers
Where # of neurons in first layer > # of neurons in second layer
