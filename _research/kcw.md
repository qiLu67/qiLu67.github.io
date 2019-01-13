---
title: "Mine Locomotive Collision Warning System"
image:
  path: /images/KCW.png
  thumbnail: /images/KCW.png
  caption:
---
# Objective
Developing mine locomotive collision warning system to achieve: 1. real-time obstacle detection; 2. complex road condition detection; and 3. mine locomotive localization.

# Abstract
This project develops a collision warning system for underground mine locomotives. The developed system utilizes a 2D LiDAR to achieve the obstacle detection with the collection angle of 270 degrees and detection range beyond 60 meters. The RFID technology is employed for two purposes: complex road condition detection, such as curved road and mine locomotive localization. The pre-deployed RFID tags include the position, traveling direction and track number information. The communication between the locomotives is achieved with LoRa wireless data communication technology. The data processing and human machine interaction is achieved with the industrial grade tablet.

# Experiments

<figure style="width: 600px" class="align-center">
  <img src="/images/kcw_hmi.jpg" alt="">
  <figcaption></figcaption>
</figure>
**Figure 1. Human machine interface**

<figure style="width: 600px" class="align-center">
  <img src="/images/kcw_test_environment.png" alt="">
  <figcaption></figcaption>
</figure>
**Figure 2. Experimental environment**

<figure style="width: 600px" class="align-center">
  <img src="/images/kcw_results.png" alt="">
  <figcaption></figcaption>
</figure>
**Figure 3. Obstacle detection results: the blue dot is the point cloud from the LiDAR and the red box is the predefined warning area.**

---
