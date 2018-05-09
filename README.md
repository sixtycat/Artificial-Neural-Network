# Artificial-Neural-Network

Artificial Neural Network, all fully connected layers, including forward propagation and backpropagation functions.

This file is for MNIST dataset.

Using Relu function as activition function, which can be modified in activaion_func and activation_fcnp.

The layers are set in the list using the unit number such as [784,64,64,10]. The first is input layer, the last is output layer. Softmax and cross entropy is used.

Pay attention to the Path you'll be use.

The net is a dictionary, the key for each layer is "'layer_wbaz' + str(i)", where i is an positive integer.

The weight, bias, value_a, value_z are saved in the values corresponding to the keys. That is:
net_dict['layer_wbaz' + str(1)][0] is the weight between input and the first hidden layer;
net_dict['layer_wbaz' + str(1)][1] is the bias between input and the first hidden layer;
net_dict['layer_wbaz' + str(1)][2] is the value of the first hidden layer;
net_dict['layer_wbaz' + str(1)][3] is the activation value of the first hidden layer;
