---
layout: page
title: Transformer-RL
description: Transformer RL for games
img: /assets/img/trl.png
importance: 2
github: https://github.com/udion/Transformer-RL
---

[code](https://github.com/udion/Transformer-RL)

Recent times have witnessed sharp improvements in reinforcement learning tasks using deep reinforcement learning techniques like Deep Q Networks, Policy Gradients, Actor Critic methods which are based on deep learning based models and back-propagation of gradients to train such models. An active area of research in reinforcement learning is about training agents to play complex video games, which so far has been something accomplished only by human intelligence. Some state of the art performances in video game playing using deep reinforcement learning are obtained by processing the sequence of frames from video games, passing them through a convolutional network to obtain features and then using recurrent neural networks to figure out the action leading to optimal rewards. The recurrent neural network will learn to extract the meaningful signal out of the sequence of such features. In this work, we propose a method utilizing a transformer network which have recently replaced RNNs in Natural Language Processing (NLP), and perform experiments to compare with existing methods.