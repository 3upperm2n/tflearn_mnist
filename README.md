# tflearn_mnist
tflearn on mnist datasets

## Supported networks:
* LeNet ([ref](http://eblearn.sourceforge.net/beginner_tutorial2_train.html))
  * conv (5x5, 6 feature maps), max_pooling (2x2) [original l2 pooling](http://neuralnetworksanddeeplearning.com/chap6.html)
  * conv (6x6, 16 feature maps), max_pooling (2x2)
  * conv (6x6, 120 feature maps)
  * fully-connected, 84
  * full-connected, 10, softmax
  
* Default
 * full-connected, 20 , ReLU
 * full-connected, 10, softmax


## Author
Leiming Yu
[[homepage](http://www1.coe.neu.edu/~ylm/)]
[[github](https://github.com/3upperm2n/)]

ylm@ece.neu.edu


## To Do
* AlexNet ([paper](https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf))
