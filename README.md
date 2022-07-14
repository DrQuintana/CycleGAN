# CycleGAN

This notebook utilizes a CycleGAN architecture to add Monet-style to photos. For this tutorial, we will be using the TFRecord dataset. Import the following packages and change the accelerator to TPU.

For more information, check out TensorFlow and Keras CycleGAN documentation pages.

It is based on the tutorial from Amy Jang. The main addition is the usage of a 9 "ResNet" blocks generators and a decreasing learning rate, as is described in the CycleGAN paper.
