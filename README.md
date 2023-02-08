# M3-exercise-1
The first assignment 


# 1. First we imported the needed libraries.
# 2. Applied scaling to normalize the data. Afterwards using the onehotenconder to change the categorical data to labels. 
# 3. Then we created a feedforward network. The goal is to predict an output given a set of inputs. The network consists of layers of interconnected nodes, where each node represents a mathematical operation, and the edges represent the flow of data between nodes. Then the network is trained to minimze the error between the predicted output and the actual output using an optimization algorithm gradient descent.
# 4. next step is the feedforward evaluation. During this process, the input is passed through the network, layer by layer, and the values of each node are calculated using the activation function and the weights of the connections. The final output is obtained by passing the values from the last layer through the activation function of the output layer. This output represents the network's prediction for the given input. In the code we first use 1 layers with 2 inputs. 
# 5. the next steps are the gradient calculation which is performed during backpropagation, this is an algorithm that propagates the error from the output layer back through the network to update the weights. The gradients are used as the update rule for the weights in an optimization algorithm to minimize the loss and converge to a solution.

Afterwards we did it with to hidden layers and 4 inputs. The process was the same. 
