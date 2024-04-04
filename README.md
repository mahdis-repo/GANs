# GANs

This repo is a survey of different GAN architectures which are implemented in PyTorh or Tensorflow. 

### Simple Dense GAN

- Vanilla GANs are tricky to get to converge. Here is the [implementation in tensorflow]() vs. [implementation in PyTorch]().

 ![image](https://github.com/mahdis-repo/GANs/assets/145799768/35b0cd5b-60cc-491f-81e5-f590425636bc)


As you can see the generator is creating pretty desent 1s and 7s and 9s. To prevent this bias we can take a number of measures, from changing the activation function from 'ReLU' to 'SeLU' to changing the network architecture by using CNNs + Upsampling.



### Deep Convolutional GAN (DCGAN)

- A slightly more sophisticated method of implementing GANs is using Convolutions. In another [repo](https://github.com/mahdis-repo/MNIST-Classification-SupervisedLearning) I have compared how using Artificial Neural Networks vs. Convolutional Neural Networks for digit classification (the same MNIST dataset) have different accuracy outcomes and how CNNs are more efficient and more accurate since they:
  
    - Preserve the information of neighboring pixels
    - Have less parameters to train (which is less prune to overfitting)

  Here is the implemenation of [DCGAN in Tensorflow]().

![image](https://github.com/mahdis-repo/GANs/assets/145799768/3e956af5-5b21-4c7e-951f-99f72a782dcf)
