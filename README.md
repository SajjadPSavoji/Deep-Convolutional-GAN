# DCGAN

![DCGAN Overall](https://iq.opengenus.org/content/images/2019/08/1-8.PNG)

Supervised learning with convolutional networks (CNNs) has seen huge adoption in computer vision applications. Comparatively, unsupervised learning with CNNs has received less attention. In this work we hope to help bridge the gap between the success of CNNs for supervised learning and unsupervised learning. We introduce a class of CNNs called deep convolutional generative adversarial networks (DCGANs), that have certain architectural constraints, and demonstrate that they are a strong candidate for unsupervised learning. Training on various image datasets, we show convincing evidence that our deep convolutional adversarial pair learns a hierarchy of representations from object parts to scenes in both the generator and discriminator. Additionally, we use the learned features for novel tasks - demonstrating their applicability as general image representations.

# Results
In this project, DCGAN was trained on the CFAR10 Dataset. Below are some of the results of this implementation.
![training gif](https://github.com/SajjadPSavoji/Deep-Convolutional-GAN/blob/master/dcgan%20(3).gif)

# Resources
[[original paper]](https://arxiv.org/pdf/1511.06434.pdf)

[[code from tensorflow]](https://github.com/tensorflow/models/blob/master/research/slim/nets/dcgan.py)

[CFAR10 Dataset](https://www.cs.toronto.edu/~kriz/cifar.html)
