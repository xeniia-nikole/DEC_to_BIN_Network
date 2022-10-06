# DEC_to_BIN_Network
Network transferring numbers to Binary with ability to be taught (with Back Propagation, Stochastic Gradient Descent etc)

## Description 
The project is a set of handwritten methods which form a network converting numbers from decimal to binary.


The network has a learning capability by passing through the SGD method List<double[][]> trainingData, the number of cycles and the wound amount of data in each. 


When the error rate is reduced to the user-specified PARAM_PRECISION_RAT minimum, it saves itself to a file, from where it can be retrieved via the main method of the Main class and used via the console to manipulate the numbers.



