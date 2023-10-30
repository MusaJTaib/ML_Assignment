# Conditional GAN Tutorial

## GAN

GANs are ML models that create synthetic data that looks like real data, it does so by using a generator model (which creates the synthetic data)
and a discriminator model (which tries to guess if data is real or synthethic). They are trained against each other until the generator can
generate data that fools the discriminator model well enough.


## Conditional GAN

Regular GANs do not specify the class of the generated data, and conditional GANs solve this problem by inserting class information in the inputs
of both the generator and discriminator models. The result is that we can now control the class of the output and associate it with a label. This can be used to generate a labeled dataset of synthetic images, for example.


## Tutorial
The tutorial is contained within the notebook, just follow along and run the cells.

