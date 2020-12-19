---
layout: page
title: Pose2Action
description: Action recognition using poses
img: /assets/img/p2a.png
importance: 2
github: https://github.com/udion/Pose2Action
---

[code](https://github.com/udion/Pose2Action)

The task here is to recognise the actions done by a human in an input 2-D video. The pipe line fist performs the 3-D pose estimation and later uses it as feature vectors to perform classification, the classifier is based on LSTM networks and experiments were performed to check whether using 2-D projections of poses instead of 3-D projections can still yeild valuable results.