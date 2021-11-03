# Unforgeable

## Inspiration
Computer generated imagery is the application of computer graphics to create or contribute to images in art, printed media, video games and simulations. There are a few popular tools and techniques used in computer generated imagery like Photoshop, green screen, generative adversial networks and animative modelling. Besides the cool and satisfactory results of CGI, there are few situations where it becomes a great threat to the society. They look very realistic such that it becomes difficult to distinguish them from photographic images and they are immune to the state-of-the-art deep fake detection techniques. There is a high risk of using these images in fraudulent activities as a replacement to the original face for faking the identity. Also, there are significant records of portraying false morphed images of an individual in social media.

## What it does
The webapp takes in the suspicious image as input and makes prediction using the pretrained model. The result comprises of two components:

- Photographic confidence
- Tampered confidence

## How we built it
We have constructed a convolutional neural network and trained it on multiple image datasets containing real and tampered images. The model with least generalization error is chosen and saved. Transfer learning is implemented using the pretrained model for faster inference and hence the predictions are super fast and accurate.

## Challenges we ran into
We have also deployed our web app using Heroku Cloud. You can access it on

## Accomplishments that we're proud of
- The deployment of the model into the django app took very long than expected, since we tried to run the inference on PyTorch CPU version.
- Building the UI is also a time-consuming activity and it demanded a full-fledged work time.

## What we learned
- We learnt how to implement transfer learning for Convolutional Neural Network (CNN) models and deploying them on to the django application.
- We also learnt some basic video editing to make the video pitch for the project. The challenging part is to build the video very quick by learning parallely.

## What's next for  Unforgeable
- We have planned to improvise the accuracy of the model by collecting more samples of the photographic and computer graphic images and thinking to integrate this system with the deep fake detection algorithms for building a highly robust system of image forgery detection.
