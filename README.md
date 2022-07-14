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

#Results

![alt text](https://www.kaggleusercontent.com/kf/100608821/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..SJYdvr75eRZ2dPZu4DAu5Q.YzH8L1xXZOuDmVfxYhCx2vKtfuuFaTrIJpdNcn3ardhgibPt4Yk3xyIZrMN8n9sgf1zgFBAdkt48uOrtWhXwngc3qRRaA4vP0UpYXOIUVI_lufPgDyIot548NVxk0tARUZrw79lmp8Er3tUrABR6jiax0ln4UfIivfZi4GngHMtyTo-i00xB7cCDVwI9PvjgSCh6VpPmH3HJZ4i1Ss2rHJyyd0GrPaqhc1_tcZ3C5f6HyVohrOZrDeIz6OjyzCOwZn_39BntRAOY1Bw8XNxZIvK-wR8Kh-Bs2xB0iPQGV8J_w5Rt_oifL10zlQcs7WA5f3zkBszP3IIHgUvPld6yQWuCGWjA4kjt8gBCbyDP_g6h0Ryr4orFQmvkvVyFdDVpHHgHxHaJKtQ49cytrALPktYPG1kKIIetLdBCbUGbcIZVcnK5cOJKr1H5lslSYDzUPfXixgEA9RNWPQ4DteJGi3BPCjTcZTCvJaogGBAulJU6qm6QyXpHuVWO3-5zdYljMFFGksvWjFGRf6mZEufScu4tYmZXIrYOfrma13_E4GDMJF_xta_Mq5BislyGnRP5PLn901sWmeC03JTXrjzGx1ebIl8McOzBFViyirXedsNM-d7vKPgEFx9i6qp8-B6eYkuuMz-NKXRFXbW__ImZD-qNE3_oyyvJDjCmwH8TJQM._oFjM3YWicNlNcx0lJJXHg/__results___files/__results___40_0.png)
