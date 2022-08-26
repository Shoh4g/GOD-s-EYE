# GODs-EYE

A Brain Tumour Classifier to detect cancer from MRI Images 

Integrated multilayer perceptron (MLP) for image identification. Prevented curse of dimensionality and overfitting by utilizing the CNN model’s template matching technique and convolution filters.

Utilized pooling layers (max pool) to reduce the dimension of the feature map as well as numbers of parameters to learn and the amount of computation performed in the network. Added a padding layer to enable the convolutional filter for capture all features from the image.

Implemented flattening operation to flatten the output of the convolutional layers to create a single long feature vector and connected it to the final classification model. Applied transfer learning via Mobile net modeling architecture to increase the accuracy of the model as well as avoid latency.
