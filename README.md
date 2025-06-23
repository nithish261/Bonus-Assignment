# Bonus-Assignment

Name: Nithish Reddy Thakkiti

Student ID: 700764837

Course: CS5720 Neural Networks and Deep Learning

Bonus Assignment: Neural Networks


Overview


This assignment explores core concepts in Generative Adversarial Networks (GANs), with a focus on Conditional GANs (cGANs) and image-to-image translation tasks. It highlights key architectural differences, training objectives, and real-world applications.


Short Answers
1. How does a Conditional GAN differ from a vanilla GAN?
In a Conditional GAN (cGAN), both the generator and discriminator receive additional label information (also called a class condition). This allows the generator to produce outputs that are not just realistic, but also conditioned on a desired category (e.g., digits, facial expressions).
Real-world application:


Emotion-based face generation (e.g., generating a happy or sad face).


Fashion design: generating clothes tailored to a specific gender or style.


2. What does the discriminator learn in image-to-image GANs?
The discriminator learns to differentiate between:


Real image pairs: (input image, ground truth)


Fake image pairs: (input image, generated output)


Why is pairing important?
Without proper pairing, the generator may produce outputs that look good but don’t correspond correctly to the input. Pairing ensures that the network learns meaningful transformations, like converting sketches to realistic images or night scenes to day scenes.
Suggested Extensions
If you're continuing with this project, consider implementing:


A cGAN on the MNIST dataset conditioned on digit labels.


A Pix2Pix-style image-to-image translation GAN using datasets like facades or maps.
