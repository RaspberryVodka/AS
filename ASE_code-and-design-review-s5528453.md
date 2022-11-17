# Object Recognition

## Abstract

Identify the objects contained within the picture and describe the objects contained in the picture through text. My aims and outcomes are to accurately identify the objects in the picture and to describe the main objects contained in the picture.

## Detailed Description
### Convolutional neural network architectures.

Unlike conventional neural networks, the neurons in each layer of a convolutional neural network are arranged in 3 dimensions: width, height and depth.

Convolutional neural networks consist of these types of layers: an input layer, a convolutional layer, a ReLU layer, a pooling layer and a fully connected layer (the fully connected layer is the same as in a regular neural network). By stacking these layers together, a complete convolutional neural network can be constructed.

Recognition and classification of objects in pictures by building convolutional neural network architectures.

### R-CNN

1. Generate initial sub-segmentation, we generate many candidate     regions
2. Use greedy algorithm to recursively combine similar regions into larger ones 
3. Use the generated regions to produce the final candidate region proposals 

Reference:

    https://towardsdatascience.com/convolutional-neural-networks-explained-9cc5188c4939

    https://towardsdatascience.com/r-cnn-fast-r-cnn-faster-r-cnn-yolo-object-detection-algorithms-36d53571365e

### Datasets

The dataset I am using is CIFAR-10

### Arcitecture Proposal

I will use neural networks to implement my project reference to model architectures:

1. ObjectNet-Baseline
2. R-CNN
3. Faster R-CNN
4. CNN

## References
Reference paper:

1. Densely Connected Convolutional Networks(CVPR 2017  ·  Gao Huang, Zhuang Liu, Laurens van der Maaten, Kilian Q. Weinberger ·)

2. Going Deeper with Convolutions(CVPR 2015  ·  Christian Szegedy, Wei Liu, Yangqing Jia, Pierre Sermanet, Scott Reed, Dragomir Anguelov, Dumitru Erhan, Vincent Vanhoucke, Andrew Rabinovich ·)

3. Striving for Simplicity: The All Convolutional Net(21 Dec 2014  ·  Jost Tobias Springenberg, Alexey Dosovitskiy, Thomas Brox, Martin Riedmiller)