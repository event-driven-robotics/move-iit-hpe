---
layout: default
title: Home
---

# move-iit-hpe

<video controls autoplay width="100%" video="100%" style="width:100%; height:100%"><source type="video/mp4" src="assets/vid/side-by-side.mp4"></video>

move-iit-hpe is a Human Pose Estimation (HPE) dataset and competition captured with event-cameras [ ]. The dataset tests, in particular, the ability to deal with moving event-camera with cluttered scene and large variations in dynamics.

The dataset consists of 11 subjects performing 17 actions. The subject is captured with 3 cameras: a stationary event-camera, a moving event-camera, and a moving rgb camera. Each action is repeated twice, with the moving camera moving "slow" and "fast". A VICON motion capture system is used for joint ground-truth, using the standard 13 joint model [ ].

| Camera            | Version  | Resolution |
| :---------------- | :------: | ----:      |
| static event-camera |   Prophesee ATIS EVK4   | 1280x720      |
| dynamic event-camera |   Prophesee ATIS EVK4   | 1280x720      |
| rgb camera    |  real-sense V?   | 640x480      |


### Why event-cameras?

explain what and why event-cameras. especially for HPE.

### TO-DO

  - [x] logo/simple image for dataset
  - [ ] diagram of layout of cameras and subject
  - [ ] collect and media from stefano, yvonne, luna, gaurvi etc.
  - [x] example videos from each of the sensors
  - [ ] upload sample dataset - hosting?
  - [ ] instructions and script for loading data
  - [ ] dockerfile and instructions for testing
  - [ ] autoplay video and move to centre