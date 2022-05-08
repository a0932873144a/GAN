# GAN
hw6_gan.py:

This program make machine generate anime faces with GAN.
It(Generator) first generate some random anime faces(complex Distribution) depending on the database(normal Distribution).
Then it(Discriminator) will rate the pictures on a scale of 0 to 1.
In the end, it(dcGAN) will keep training Generator and Discriminator.
You can find that the pictures it generates will more and more like a real anime face instead of wired color block.

anime_stylegan2_google_colab_example.py:

In this program, it will mostly deal with people's faces.
There are three features of styleGAN.
First, it can combine two different faces to generate a new face with their features.
Secondly, it can generate the changing process of two given pictures. And these generated pictures will look like a real faces.
Last, similarly to the former, it can generate the changing process of one's left face to right face. And of course, these generated pictures will look like a real faces.
Besides these features, we can add "noise" to make the generated pictures more random.
With above features, it can generate random and real picture. It can also generate faces based on the inputted image.
