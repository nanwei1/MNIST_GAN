# MNIST_GAN

Generative Adverserial Network using the MNIST handwritten digit dataset
Based on work by BeierZhu: https://github.com/BeierZhu/GAN-MNIST-Pytorch

## Example Output Generated by Fully-Connected Net:
Epoch 1:
<p align="center"> <img src=".//MNIST_GAN_FC/samples/fake_images-1.png" width="300"/> </p>
Epoch 5:
<p align="center"> <img src=".//MNIST_GAN_FC/samples/fake_images-5.png" width="300"/> </p>
Epoch 10:
<p align="center"> <img src=".//MNIST_GAN_FC/samples/fake_images-10.png" width="300"/> </p>
Epoch 20:
<p align="center"> <img src=".//MNIST_GAN_FC/samples/fake_images-20.png" width="300"/> </p>
Epoch 50:
<p align="center"> <img src=".//MNIST_GAN_FC/samples/fake_images-50.png" width="300"/> </p>
Epoch 100:
<p align="center"> <img src=".//MNIST_GAN_FC/samples/fake_images-100.png" width="300"/> </p>

## Example Output Generated by CNN - clear example of mode collapse of GAN:
Epoch 1:
<p align="center"> <img src=".//MNIST_GAN_CNN/samples_mode_collapse/fake_images-1.png" width="300"/> </p>
Epoch 5:
<p align="center"> <img src=".//MNIST_GAN_CNN/samples_mode_collapse/fake_images-5.png" width="300"/> </p>
Epoch 10:
<p align="center"> <img src=".//MNIST_GAN_CNN/samples_mode_collapse/fake_images-10.png" width="300"/> </p>
Epoch 20:
<p align="center"> <img src=".//MNIST_GAN_CNN/samples_mode_collapse/fake_images-20.png" width="300"/> </p>
Epoch 50:
<p align="center"> <img src=".//MNIST_GAN_CNN/samples_mode_collapse/fake_images-50.png" width="300"/> </p>

## Example Output Generated by CNN - improved by adding minibatch discrimination:
References:

- https://gist.github.com/t-ae/732f78671643de97bbe2c46519972491

- https://arxiv.org/abs/1606.03498

- https://mc.ai/gan-ways-to-improve-gan-performance/

Epoch 1:
<p align="center"> <img src=".//MNIST_GAN_CNN/samples/fake_images-1.png" width="300"/> </p>
Epoch 5:
<p align="center"> <img src=".//MNIST_GAN_CNN/samples/fake_images-5.png" width="300"/> </p>
Epoch 10:
<p align="center"> <img src=".//MNIST_GAN_CNN/samples/fake_images-10.png" width="300"/> </p>
Epoch 15:
<p align="center"> <img src=".//MNIST_GAN_CNN/samples/fake_images-15.png" width="300"/> </p>
Epoch 20:
<p align="center"> <img src=".//MNIST_GAN_CNN/samples/fake_images-20.png" width="300"/> </p>

