# Object-recognition-with-tensorflow

We have created a variety of modern Neural Networks like Deep Convolutional Neural Networks, VGG Networks, Residual Neural Networks (ResNet), Highway Networks and Dense Neural Networks purely on tensorflow and tried their performance on object recognition and classification on the CIFAR-10 and CIFAR-100 datasets.

#### DenseNet
DenseNet is a network architecture where each layer is directly connected to every other layer in a feed-forward fashion (within each dense block). For each layer, the feature maps of all preceding layers are treated as separate inputs whereas its own feature maps are passed on as inputs to all subsequent layers. This connectivity pattern yields state-of-the-art accuracies on CIFAR10/100 (with or without data augmentation) and SVHN. On the large scale ILSVRC 2012 (ImageNet) dataset, DenseNet achieves a similar accuracy as ResNet, but using less than half the amount of parameters and roughly half the number of FLOPs.

<img src="https://cloud.githubusercontent.com/assets/8370623/17981494/f838717a-6ad1-11e6-9391-f0906c80bc1d.jpg" width=502 height=309 />

#### ResNet, VGG-19, CNN-34

https://image.slidesharecdn.com/lenettoresnet-170509055515/95/lenet-to-resnet-17-638.jpg?cb=1494309688

### References

Very Deep Convolutional Networks for Large-Scale Image Recognition
K. Simonyan, A. Zisserman
arXiv:1409.1556

Kaiming He and (2015). Deep Residual Learning for Image Recognition. CoRR, abs/1512.03385, .

Gao Huang and (2016). Densely Connected Convolutional Networks. CoRR, abs/1608.06993

Rupesh Kumar Srivastava and (2015). Highway Networks. CoRR, abs/1505.00387

Nitish Srivastava, Geoffrey Hinton, Alex Krizhevsky, Ilya Sutskever, and Ruslan Salakhutdinov.
Dropout: A simple way to prevent neural networks from overfitting. J. Mach.
Learn. Res., 15(1):1929–1958, January 2014.

Jost Tobias Springenberg, Alexey Dosovitskiy, Thomas Brox, and Martin A. Riedmiller.
Striving for simplicity: The all convolutional net. CoRR, abs/1412.6806, 2014.
