# Resnet_Pytorch_Implementation
Since AlexNet, the state-of-the-art CNN architecture is going deeper and deeper. While AlexNet had only 5 convolutional layers, the VGG network and GoogleNet (also codenamed Inception_v1) had 19 and 22 layers respectively.

However, increasing network depth does not work by simply stacking layers together. Deep networks are hard to train because of the notorious vanishing gradient problem — as the gradient is back-propagated to earlier layers, repeated multiplication may make the gradient infinitively small. As a result, as the network goes deeper, its performance gets saturated or even starts degrading rapidly.
Before ResNet, there had been several ways to deal the vanishing gradient issue, for instance, adds an auxiliary loss in a middle layer as extra supervision, but none seemed to really tackle the problem once and for all.

For go into furter details check this medium blog post::
https://towardsdatascience.com/an-overview-of-resnet-and-its-variants-5281e2f56035
                                     
