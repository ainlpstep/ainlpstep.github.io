---
layout: post
title: "Frozen parameters"
author: "nlp"
categories: pytorch
tags: [pytorch,NN]
---
In a NN, parameters that don't compute gradients are usually called **frozen parameters** [link](https://pytorch.org/tutorials/beginner/blitz/autograd_tutorial.html#sphx-glr-beginner-blitz-autograd-tutorial-py)

In fine-tuning a pre-trained network, we **freeze** most of the model and typically only modify the classifier layers to make predictions on new labels.
