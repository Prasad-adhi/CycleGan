The goal of this project is to explore the problem of training
style transfer models for image generators. We also want to
explore image generation itself and create the most accurate
generated images that we can. We are doing so by exploring
and testing a Generative Adversarial Network architecture
called CycleGANs as the primary method for training style
transfer models.

We have created a custom generator and discriminator architecture for the network. The generator is an autoencoder with downsampling layers and upsampling layers. While The discriminator layer is a collection of layers that are the same depth as the generator to prevent the discriminator from detecting all the images as fake given by the generator. Given below are the diagrams depicting the architectures of both the generator and the discriminator.




