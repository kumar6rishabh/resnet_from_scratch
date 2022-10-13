# resnet_from_scratch
This project focuses on implementing the RESNET18 paper from scratch in PyTorch.

The project was aimed at improving the relm of image recognition using something called the skip connections. The main idea was to let the output of the previous layer be directly connected with the output of the later layers. Each such block with such skip connections were called Residual blocks. One of the main problems related to the was the difference in size of the feature images in the intermediate layers and also the num of such features. The first problem was tackled by padding and the second problem was solved using several 1*1 convolution masks.
