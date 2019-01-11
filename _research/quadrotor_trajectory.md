---
title: "Robust Tracking Control in GPS-denied Environments"
image:
  path: /images/quadrotor_trajectory_tracking.jpg
  thumbnail: /images/quadrotor_trajectory_tracking.jpg
  caption:
---

# Abstract
This project addresses the problem of autonomous trajectory tracking control for a quadrotor in GPS-denied environment using only onboard sensing. For the position estimation in GPS-denied environment, an open source high speed optical flow sensor PX4FLOW is adopted. The cascade inner-outer uncertainty and disturbance estimator (UDE)-based robust control scheme has been developed and applied to the attitude and position control of a quadrotor.


# Objective

Autonomous trajectory tracking control in GPS-denied environments using only onboard sensing.

<!--

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

-->

# Experimental Results

<p float="left">
  <img src="/images/quadrotor_trajectory_tracking_platform.jpg" width="600px" />
</p>
**Fig1. Experimental platform**

<p float="left">
<img src="/images/quadrotor_trajectory_tracking_environment.jpg" width="600px" />
</p>
**Fig2. Experimental environment**

{% include responsive-embed url="https://www.youtube.com/embed/F_TwVBfSw58" ratio="16:9" %}

# Related publications

1. **Q. Lu**, B. Ren, and S. Parameswaran. and Q.-C. Zhong, "<a href="http://dynamicsystems.asmedigitalcollection.asme.org/article.aspx?articleid=2652289" target="_blank">Uncertainty and Disturbance Estimator-Based Robust Trajectory Tracking Control for a Quadrotor in a Global Positioning System-Denied Environment</a>," *Journal of Dynamic Systems, Measurement and Control*, vol. 140, no. 3, p. 031001, Nov. 2017.

1. **Q. Lu**,  B. Ren, and S. Parameswaran, "Robust Tracking Control for a UAV in GPS-denied Uncertain Environments," In *Texas UAS Summit & Expo and AUVSI XPONENTIAL*, Dallas, TX, May 09-10, 2017. **(3rd Place in Poster Competition and Selected to Give a 2-min Lightning Round Talk)**

1. **Q. Lu**,  B. Ren, and S. Parameswaran, "Navigation and Control for a Quadrotor UAV in GPS-denied Environments," In *Annual Graduate School Poster Competition*, Lubbock, TX, Mar. 23-24, 2017.

1. **Q. Lu**, B. Ren, S. Parameswaran, and Q.-C. Zhong, "<a href="http://proceedings.asmedigitalcollection.asme.org/proceeding.aspx?articleid=2604365" target="_blank">Position Control of a Quadrotor Using Onboard Optical Flow Sensor</a>," in *Dynamic Systems and Control Conference*, Minneapolis, MN, Oct. 12-14, 2016.

1. J. Dai, **Q. Lu**,B. Ren, and Q.-C. Zhong, "<a href="http://proceedings.asmedigitalcollection.asme.org/proceeding.aspx?articleid=2481847" target="_blank">Robust Attitude Tracking Control for a Quadrotor Based on the Uncertainty and Disturbance Estimator</a>," in *Dynamic Systems and Control Conference*, Columbus, OH, Oct. 28-30, 2015.

---
