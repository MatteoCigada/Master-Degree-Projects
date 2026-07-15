## 1. Final Project Presentation

* Course: LAB - Human-In-The-Loop Dynamic Driving Simulator
  * Instructors: Prof. Michele Vignati, Prof. Federico Maria Ballo
* Authors: M. Atceter, M. Cigada, L. Crosta, F. D'Agostini
* Date: 24/06/2026
* Keywords: Human-In-The-Loop, Driving Simulator, DriSMI, Lane Change, Emergency Maneuver, Traffic Scenario, Cueing, Offline Simulation, Driver Comparison
* Software used: DriSMI Driving Simulator, DriveSim / VI-grade tools, MATLAB
* Goal of the project: Analyze the behaviour of real drivers inside a dynamic driving simulator and compare human-in-the-loop results with offline simulation references. The activity focuses on the design of a custom driving scenario, the implementation of traffic events, the tuning of the motion cueing strategy, the execution of real-time driving sessions, and the post-processing of the results.

The project is based on a sequence of lane-change maneuvers with increasing difficulty:

* **Maneuver 1 - Fixed blind obstacle:** a low-speed emergency lane change at the entrance of a highway, where the obstacle is partially hidden and the driver must react while entering the road.
* **Maneuver 2 - High-speed overtake:** a standard overtaking maneuver performed at higher speed, used as a safer and more regular reference case.
* **Maneuver 3 - Incoming vehicle avoidance:** a more critical event in which a truck masks an incoming vehicle until the last moment, forcing the driver to react quickly to avoid the obstacle.

The real-time simulation phase includes the construction of the road environment, the implementation of moving traffic through trigger-based logic, and the calibration of the cueing strategy. Particular attention is given to the balance between longitudinal, lateral, yaw and pitch motion cues, since the simulator motion platform cannot reproduce the full real vehicle accelerations directly.

The offline simulation phase is used to create reference cases for comparison. Simulations are performed both on custom trajectories and on trajectories recorded during the online driving sessions. For each trajectory, maximum-performance and custom-speed-profile simulations are considered, providing upper-bound and more realistic references for the human driver behaviour.

The final analysis compares different drivers in terms of reaction strategy, steering input, yaw response, lateral acceleration and grip utilization. The results highlight that the online maneuvers are mainly affected by driver perception, reaction strategy and simulator interaction rather than by the physical grip limit of the vehicle. Subjective feedback also shows that longitudinal acceleration and speed perception remain critical aspects of the simulator experience.

* PowerPoint presentation: [DRISMI final presentation](DRISMI%20final%20presentation.pptx)
* PDF presentation: [DRISMI final presentation](DRISMI%20final%20presentation.pdf)

---
