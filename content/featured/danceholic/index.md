---
date: '1'
title: 'DanceHolic'
cover: './demo.png'
github: 'https://github.com/bchiang7/spotify-profile'
external: 'https://spotify-profile.herokuapp.com/'
tech:
  - React JS
  - Tailwind CSS
  - Tensorflow (Pose Estimation model)
---

The app does human pose estimation by initializing a model and running inference on input images to predict keypoints, which are then overlaid on the images for visualization. It includes a cropping algorithm to determine the region of interest for pose estimation based on detected keypoints, enabling efficient processing of relevant image areas. Additionally, the app calculates gradients between keypoint pairs across successive frames, facilitating analysis of motion dynamics over time.
