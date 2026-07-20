---
date: 2023-07-14
title: CNN Rock Paper Scissor
subtitle: Playing Rock Paper Scissors with a Convolutional Neural Network
language: en
lang: en
permalink: /en/project/cnn-rockpaperscissor/
image:
    path: /assets/images/projects/cnnRockPaperScissor/cnnRockPaperScissor_04.png
gallery:
    - path: /assets/images/projects/cnnRockPaperScissor/cnnRockPaperScissor_02.png
    - path: /assets/images/projects/cnnRockPaperScissor/cnnRockPaperScissor_03.png
    - path: /assets/images/projects/cnnRockPaperScissor/cnnRockPaperScissor_04.png
    - path: /assets/images/projects/cnnRockPaperScissor/cnnRockPaperScissor_05.png

layout: projects
---

In the Smart Media Technology course of my media technology studies, I was significantly involved in the development of an interactive “rock, paper, scissors” game. Our group's goal was to use a convolutional neural network (CNN) to analyze the users' webcam images and recognize their hand gestures (rock, paper, or scissor) in order to compete against the computer.

The entire implementation was done in Python on the Google Colab platform. We created our own dataset with about 200 images for each hand gesture to train the CNN. In doing so, we refined a pre-trained ResNet50 model to suit our requirements. We used PyTorch as the framework, while Ray Tune and Tensorboard were used for training and visualizing the results.

Our game can be played in a specially developed Jupyter notebook on Google Colab. The notebook loads the latest model from a Git repository and performs the image recognition. To improve gesture recognition, the webcam image is cropped to the recognized hand using Mediapipe before the actual prediction is performed by our CNN. The user interface was designed using IPython widgets.

The project gave me practical experience in machine learning and artificial intelligence for interactive applications. It provided interesting insights into the challenges and possibilities of image recognition.

[Link to the game notebook for playing](
https://colab.research.google.com/drive/1YFxfhp5Srf8tqa0avC0Oa3wqk1ovVd8V?usp=sharing)
