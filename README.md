# I'm something of a painter myself

The competition is entitled "I'm something of a painter myself".
to develop a generative model trained to produce images in the style of Monet's paintings.
The goal is to design images of Claude Monet, the founder of Impressionism. 

The competition is a "Getting Started" competition: there are no prizes, no deadlines (beginning of August 2020), and no private ranking.
August 2020), nor private ranking. This competition runs indefinitely and is a resource to learn about
a resource for learning about Computer Vision concepts, generative models, and
generative models, Tensor Processing Units (TPU) and the TFRecords format for
TensorFlow.
The quality of the model, and the ranking of the competition, are determined by several
thousands of images (between 7000 and 10 000) generated in the notebook submitted by the
participant.


# CycleGAN

This notebook utilizes a CycleGAN architecture to add Monet-style to photos. For this tutorial, we will be using the TFRecord dataset. Import the following packages and change the accelerator to TPU.

For more information, check out TensorFlow and Keras CycleGAN documentation pages.

It is based on the tutorial from [Amy Jang](https://www.kaggle.com/code/amyjang/monet-cyclegan-tutorial/notebook). The main addition is the usage of a 9 "ResNet" blocks generators and a decreasing learning rate, as is described in the CycleGAN paper.
