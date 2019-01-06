---
title: "Robust Tracking Control in GPS-denied Environments"
image:
  path: /images/quadrotor_trajectory_tracking.jpg
  thumbnail: /images/quadrotor_trajectory_tracking.jpg
  caption:
---

This project addresses the problem of autonomous trajectory tracking control for a quadrotor in GPS-denied environment using only onboard sensing. For the position estimation in GPS-denied environment, an open source high speed optical flow sensor PX4FLOW is adopted. The cascade inner-outer uncertainty and disturbance estimator (UDE)-based robust control scheme has been developed and applied to the attitude and position control of a quadrotor.


# Objective

Autonomous trajectory tracking control in GPS-denied environments using only onboard sensing.

# Challenges

* Reliable navigation in GPS-denied environment;
* Fast dynamics, naturally unstable system;
* System underactuation;
* State couplings;
* Nonaffine inputs;
* Model uncertainties;
* External disturbances.

# Approaches

* PX4FLOW sensor is adopted for GPS-denied navigation;
* Uncertainty and disturbance estimator (UDE)-based cascade control scheme is developed;
* UDE-based attitude controllers are developed to deal with couplings, model uncertainties and disturbances;
* UDE-based position controllers are developed to handle
the nonaffine inputs.

<figure style="width: 1000px" class="align-left">
  <img src="/images/quadrotor_trajectory_tracking_control_scheme.jpg" alt="">
  <figcaption></figcaption>
</figure>
**Fig1. Quadrotor cascade control scheme**

# Experiments

<p float="left">
  <img src="/images/quadrotor_trajectory_tracking_platform.jpg" width="400px" />
  <img src="/images/quadrotor_trajectory_tracking_environment.jpg" width="400px" />
</p>
**Fig2. Experimental setup**

{% include responsive-embed url="https://www.youtube.com/embed/F_TwVBfSw58" ratio="16:9" %}

---
