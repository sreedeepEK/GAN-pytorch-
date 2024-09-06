## GAN-pytorch
A deep learning approach to generate anime-style face images using Generative Adversarial Networks (GANs).  

### Results

The trained model is capable of generating anime faces that are visually appealing and diverse. Below are some examples of the generated images:

<p align="center">
  <img src="https://github.com/ft-sreedeep/GAN-pytorch/blob/main/anime_training.gif" alt="alt text" width="400" />
</p>



### Overview 

This project uses a Generative Adversarial Network (GAN) to create anime-style face images from random noise. The GAN consists of a generator that learns to create realistic anime faces and a discriminator that distinguishes between real and generated images. By training these two networks together, the generator improves over time, producing high-quality, visually appealing anime faces that resemble those in the training dataset. The project demonstrates the power of GANs in generating new, unique images based on learned patterns, offering insights into both deep learning and image generation techniques.


### How It Works

* Generator: Takes in a random noise vector (latent space) and transforms it into a 64x64 image that resembles an anime face.
* Discriminator: Evaluates images and predicts whether they are real (from the training dataset) or fake (generated by the generator).
* Training Process: The generator and discriminator are trained simultaneously in a loop. The generator tries to fool the discriminator, while the discriminator tries to accurately classify real and fake images.
