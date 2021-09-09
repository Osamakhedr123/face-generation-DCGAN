# Face Generation using DCGAN

In this project, I'll define and train a DCGAN (Deep Covolutional Generative Adversarial Network) on a dataset of faces. My goal is to get a generator network to generate *new* images of faces that look as realistic as possible!

The project is broken down into sections, starting from **loading in data to defining and training adversarial networks**. At the end of the notebook, I'll visualize the results of my trained Generator to see how it performs; my generated samples should look like fairly realistic faces with small amounts of noise.

## Training Data

I'll be using the [CelebFaces Attributes Dataset (CelebA)](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) to train my adversarial networks.