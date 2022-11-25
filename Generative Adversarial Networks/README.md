# Generative Adversarial Networks
These use different networks, the generator and the discriminator. The generator tries to create new data that mimics real data. The goal of the discriminator is to distinguish between the real data and the fake data created by the generator. 

The training is done alternatively with only of the networks being trained at a time while the parameters of the other are kept constant.

The loss function is perhaps the most peculiar thing about the model. It works on the principle of min-max game. It makes use of the outputs of the discriminator to train the generator and the outputs of the generator to train the discriminator.

There are several GAN based architectures that have been used in a variety of fields such as deep-fake generation, super-resolution, etc.