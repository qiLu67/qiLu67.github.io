---
title: "Rotating Liquid Jet Impingement Cooling System"
image:
  path: /images/jet_impingement.jpg
  thumbnail: /images/jet_impingement.jpg
  caption:
---
# Objective
Developing numerical model for predicting the heat transfer performance of the the jet impingement cooling system.

# Abstract
The circular, liquid jet impingement provides a convenient way of cooling surfaces. To effectively cool the devices inside the electric vehicle, a rotating jet impingement cooling system is designed to evaluate the potential of the jet impingement for high heat flux removal. The liquid used for jet impingement is automatic transmission fluid. The jet impingement system consists of a rotating pipe with two nozzles and a cylindrical ring which is attached to the heat source. The numerical simulation using the commercial code is performed to determine the heat flux removal performance over the cylindrical surface. The numerical results are compared with the empirical formula and experimental measurements from the literature. Furthermore, the effects of the Reynolds number and pipe rotation on the jet impingement cooling performance are also investigated.


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

# Simulation

<figure style="width: 600px" class="align-center">
  <img src="/images/jet_impingement_emprical_comparison.jpg" alt="">
  <figcaption></figcaption>
</figure>
**Fig1. Comparison of numerical results and empirical formula**

<figure style="width: 600px" class="align-center">
  <img src="/images/jet_impingement_comparison_with_measurements.jpg" alt="">
  <figcaption></figcaption>
</figure>
**Fig2. Comparison with experimental measurements**

<figure style="width: 600px" class="align-center">
  <img src="/images/jet_impingement_VOF.png" alt="">
  <figcaption></figcaption>
</figure>
**Fig3.Volume fraction of ATF for different Reynolds numbers and rotation speeds**

# Related publications

1. **Q. Lu**, S. Parameswaran, and B. Ren, "Heat Transfer by a Rotating Liquid Jet Impingement Cooling System," in *International Mechanical Engineering Congress & Exposition*, Pittsburgh, PA, Nov. 09-15, 2018.

1. **Q. Lu**, and S. Parameswaran, "Rotating Liquid Jet Impingement Cooling System," in *OpenFOAM Conference North America*, Detroit, MI, Oct. 30, 2018.

---
