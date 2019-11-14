1. **Convolution** : A convolution in a convolution neural network is a linear operation when done upon a mattrix data activates features i.e gradients, edges etc. That means it activats the connects with strongest features.

2. **Filters/Kernels** : A filter in a convolution neural network is a channel through which a feature is extracted. Allows only the values that are in the range of the learnt function.
3. **Epochs** : The number of iterations a training algorithm has seen over the whole test data. 
4. **1x1 Convolution** : The "1x1" convolution simply maps an input pixel with all it's channels to an output pixel, does not look around itself. It is often used to reduce the number of depth channels, since it is often very slow to multiply volumes with extremely large depths
5. **3x3 Convolution** : The "3x3" convolution works over the mattrix data of size greater than or equal to 3, slideing over the mattrix from left to right, top to bottom taking dot products of the individual mattrix elements then summing it all over.
6. **Feature Maps** : The feature map is the output of one filter applied to the previous layer. A given filter is drawn across the entire previous layer, moved one pixel at a time. Each position results in an activation of the network and the output is collected in the feature map

7. **Activation Function** : A activation function is special function for conditioning output, can be thought as an digital neuron, when to fire or not, depending on the given input value.
8. **Receptive Field** : Receptive field in CNN is defined as the region that recieves the partial(can be total when size of i/p=recep field size) input field from a given field , and that field is only responsible for the corresponding activations.
