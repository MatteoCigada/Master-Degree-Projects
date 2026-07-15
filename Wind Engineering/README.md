## 1. Lab 04 - Vehicles: Effect of Crosswind on Road Vehicles

* Course: Wind Engineering
  * Professor: Prof. D. Rocchi
  * Assistant: F. Zanelli
* Authors: G. Caldieron, M. Cigada, A. Ciussi, A. Galvanini, A. Gottardo
* Academic Year: 2025 - 2026
* Keywords: Crosswind, Road Vehicle, Lorry, Rollover, Turbulence Intensity, Load Ratio, Wheel Lift-Off, PID Driver Model, Double Lane Change, Roll Stiffness Distribution
* Software used: MATLAB / numerical simulation scripts
* Goal of the project: Analyze the effect of lateral turbulent wind on the dynamic response and rollover risk of a road vehicle. The vehicle considered is a lorry travelling at constant longitudinal speed across different wind histories, while the aerodynamic action of the wind is applied laterally. The model includes lateral, yaw and roll dynamics, and the driver is represented through a path-following control system.

The project investigates the following aspects:

* **Rollover speed in different wind histories:** the minimum normalized vertical wheel load is evaluated for different combinations of mean wind speed and turbulence intensity. The analysis shows that turbulence intensity is the dominant factor in triggering critical unloading and wheel lift-off.
* **Load ratio effect:** the payload ratio is varied to study how the position of the center of mass affects rollover safety. Lightly loaded configurations are more critical because the static load distribution may leave one axle more vulnerable to unloading.
* **Driver effect in a double lane change:** the driver is modeled as a preview path-follower controller. The influence of proportional gain, derivative gain and look-ahead distance is analyzed in terms of trajectory tracking, steering activity, sideslip, wheel load and rollover risk.
* **Sensitivity analysis:** additional parameters are varied, including the road friction coefficient, the front/rear roll stiffness distribution and the longitudinal position of the payload center of mass.

The main conclusion is that crosswind-induced rollover cannot be evaluated only from the mean wind speed. Turbulence intensity, payload distribution, driver/path-following strategy, road grip and roll stiffness distribution all contribute to the available safety margin. In particular, the most critical cases occur when strong turbulent gusts combine with unfavorable load distribution and aggressive steering transients.

* Report section: [Group V report - vehicles](GroupV_report_vehicles.pdf)
* Presentation: [Group V presentation - vehicles](GroupV_presentations_vehicles.pdf).

---
