# Unforgeable

## Inspiration
Computer generated imagery is the application of computer graphics to create or contribute to images in art, printed media, video games and simulations. There are a few popular tools and techniques used in computer generated imagery like Photoshop, green screen, generative adversial networks and animative modelling. Besides the cool and satisfactory results of CGI, there are few situations where it becomes a great threat to the society. They look very realistic such that it becomes difficult to distinguish them from photographic images and they are immune to the state-of-the-art deep fake detection techniques. There is a high risk of using these images in fraudulent activities as a replacement to the original face for faking the identity. Also, there are significant records of portraying false morphed images of an individual in social media.

## What it does
The webapp takes in the suspicious image as input and makes prediction using the pretrained model. The result comprises of two components:

- Photographic confidence
- Tampered confidence

## How we built it
We have constructed a convolutional neural network and trained it on multiple image datasets containing real and tampered images. The model with least generalization error is chosen and saved. Transfer learning is implemented using the pretrained model for faster inference and hence the predictions are super fast and accurate.

