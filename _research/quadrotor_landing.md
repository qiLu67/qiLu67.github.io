---
title: "Robust Landing Control on Moving Platform"
image:
  path: /images/quadrotor_landing.jpg
  thumbnail: /images/quadrotor_landing.jpg
  caption:
---
# Objective
Autonomously landing on moving platform with only onboard sensing.

# Abstract
This project develops an autonomous landing control approach for a quadrotor unmanned aerial vehicle (UAV) subject to wind disturbance and three-dimensional movements of the landing platform. To achieve an accurate relative position estimation of the quadrotor to the landing platform, a camera, a distance sensor and a single board computer are integrated to the quadrotor. The coordinate transformation is introduced to deal with the constraint that only the relative position information is available. The impacts of unknown ship motions are treated as part of the lumped uncertainty terms. Then the uncertainty and disturbance estimator (UDE)-based controllers are developed to achieve the accurate relative position control of the quadrotor while dealing with unknown ship motions, ground effect, state couplings and external disturbances. The UDE filter is designed based on the internal model principle to enhance the performance of the developed controller. The reference model of the relative altitude controller is modified to ensure the accurate tracking of descending commands. To maximize the capability of the developed controller, a parameter selection guideline based on the derived ship heave acceleration spectrum is provided.

# Experiments

<figure style="width: 600px" class="align-center">
  <img src="/images/quadrotor_landing_quadrotor_platform.jpg" alt="">
  <figcaption></figcaption>
</figure>
**Figure 1. Quadrotor platform**

<figure style="width: 600px" class="align-center">
  <img src="/images/quadrotor_landing_ship_motion_simulator.jpg" alt="">
  <figcaption></figcaption>
</figure>
**Figure 2. Ship motion simulator**

<figure style="width: 600px" class="align-center">
  <img src="/images/quadrotor_landing_experimental_environment.jpg" alt="">
  <figcaption></figcaption>
</figure>
**Figure 3.Experimental environment**

## Landing on vertically heaving platform

{% include responsive-embed url="https://www.youtube.com/embed/KxWxJ1CMrhI" ratio="16:9" %}

## Landing on three-dimensional moving platform with wind

<figure style="width: 800px" class="align-center">
  <img src="/images/quadrotor_landing_experimental_results.png" alt="">
  <figcaption></figcaption>
</figure>

# Related publications

1. **Q. Lu**, B. Ren, and S. Parameswaran., "<a href="https://arc.aiaa.org/doi/10.2514/1.G003073" target="_blank">Shipboard Landing Control Enabled by an Uncertainty and Disturbance Estimator</a>," *Journal of Guidance, Control, and Dynamics*, vol. 41, no. 7, pp. 1502-1520, Jul. 2018.

---
