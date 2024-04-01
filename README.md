# GANs

This repo is a survey of different GAN architectures which are implemented in PyTorh or Tensorflow. 

### Simple Dense GAN

- Vanilla GANs are tricky to get to converge. Interestingly, in the very first try my [simple dense GAN](https://github.com/mahdis-repo/GANs/blob/main/First_Dense_GAN_1_MNIST.ipynb) didn't converge and the discriminator won! Since it got pretty good, the generator could'nt find a mapping for guassian noise to the latent distribution of the MNIST dataset.

  ![image](https://github.com/mahdis-repo/GANs/assets/145799768/9261ca1f-a283-4f63-9f85-59ed0c0d425e)





### Deep Convolutional GAN (DCGAN)

- A slightly more sophisticated method of implementing GANs is using Convolutions. In another [repo](https://github.com/mahdis-repo/MNIST-Classification-SupervisedLearning) I have compared how using Artificial Neural Networks vs. Convolutional Neural Networks for digit classification (the same MNIST dataset) have different accuracy outcomes and how CNNs are more efficient and more accurate since they:
  
    - Preserve the information of neighboring pixels
    - Have less parameters to train (which is less prune to overfitting)
  
