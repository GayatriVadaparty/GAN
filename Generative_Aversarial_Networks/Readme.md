Generative adversarial networks (GANs) are neural networks that generate media, like images, music, speech, or text, that is similar to what humans produce.

It has been  “the most interesting idea in the last 10 years” in the field of machine learning. This repository has code which is implementing a generative model

Generative adversarial networks can also generate high-dimensional samples such as images. In this project, I'm going to use a GAN to generate images of handwritten digits. For that, I’ll train the models using the MNIST dataset of handwritten digits, which is included in the torchvision package.

### The Architecture of Generative Adversarial Networks
Generative adversarial networks consist of an overall structure composed of two neural networks, one called the generator and the other called the discriminator.

The role of the generator is to estimate the probability distribution of the real samples in order to provide generated samples resembling real data. The discriminator, in turn, is trained to estimate the probability that a given sample came from the real data rather than being provided by the generator.

These structures are called generative adversarial networks because the generator and discriminator are trained to compete with each other: the generator tries to get better at fooling the discriminator, while the discriminator tries to get better at identifying generated samples.
