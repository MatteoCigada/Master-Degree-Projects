# Advanced Motorsport Engineering

This folder contains the laboratory reports and seminar notes developed for the **Advanced Motorsport Engineering** course of the M.Sc. in Mechanical Engineering - Automotive and Motorsport Engineering at Politecnico di Milano.

* Course: Advanced Motorsport Engineering
  * Instructors: Prof. M. Gobbi, Prof. S. Melzi
* Authors: M. Cigada, F. D'Agostini, S. D'Incà
* Academic Year: 2025 - 2026
* Main topics: Motorsport Vehicle Dynamics, Lap Time Simulation, Tires, Aerodynamics, Braking System Design, Telemetry Analysis, Race Engineering
* Main software/tools used: MATLAB, OpenLAP, Set4T, WinTax, VI-CRT / VI-grade
* [Link to Laboratory Reports and Seminar Notes (PDF)](Motorsport_Engineering_Reports.pdf)

---

## 1. Lab00 - Basics

* Course: Advanced Motorsport Engineering
  * Instructors: Prof. M. Gobbi, Prof. S. Melzi
* Authors: M. Cigada, F. D'Agostini, S. D'Incà
* Academic Year: 2025 - 2026
* Keywords: Cornering Speed, Downforce, Friction Limit, Coast-Down Test, Rolling Resistance, Drag Area, Load Transfer, Aerodynamic Balance
* Software used: MATLAB
* Goal of the laboratory: Review fundamental calculations used in motorsport vehicle performance analysis. The laboratory includes basic estimations of cornering speed with and without aerodynamic downforce, simplified lap time calculations, coast-down analysis for drag and rolling resistance identification, vertical load computation under braking, and aerodynamic coefficient estimation from suspension displacement data.
* [Link to Laboratory Reports and Seminar Notes (PDF)](Motorsport_Engineering_Reports.pdf)

---

## 2. Lab01 - Tires

* Course: Advanced Motorsport Engineering
  * Instructors: Prof. M. Gobbi, Prof. S. Melzi
* Authors: M. Cigada, F. D'Agostini, S. D'Incà
* Academic Year: 2025 - 2026
* Keywords: Tire Warm-Up, Tire Thermal Model, Toe Angle, Aerodynamic Balance, Weight Distribution, Friction Law, Slip Speed, Tread Temperature, Response Surface Modeling, Neural Network
* Software used: MATLAB, Set4T
* Goal of the laboratory: Analyze the influence of setup parameters on tire temperature, grip, and lap time evolution. The first part studies tire warm-up under different ambient conditions by varying toe angle, aerodynamic balance, and weight distribution. The second part focuses on the estimation of a friction law as a function of slip speed and tread temperature, comparing response surface models and neural networks while discussing the limitations imposed by the available experimental data.
* [Link to Laboratory Reports and Seminar Notes (PDF)](Motorsport_Engineering_Reports.pdf)

---

## 3. Lab02 - Lap Time Simulator

* Course: Advanced Motorsport Engineering
  * Instructors: Prof. M. Gobbi, Prof. S. Melzi
* Authors: M. Cigada, F. D'Agostini, S. D'Incà
* Academic Year: 2025 - 2026
* Keywords: Lap Time Simulation, OpenLAP, Point-Mass Model, Fuel Load, Isochrone Maps, Aerodynamic Setup, Drag, Downforce
* Software used: MATLAB, OpenLAP
* Goal of the laboratory: Evaluate the performance of a Tatuus FA010 vehicle on different circuits using a point-mass lap time simulator. The analysis first quantifies the effect of fuel mass on lap time and then builds isochrone maps to study the trade-off between drag and downforce. The final objective is to identify the most suitable aerodynamic configuration for different track layouts, also considering practical race-engineering factors such as fuel consumption, tire wear, driver confidence, and weather conditions.
* [Link to Laboratory Reports and Seminar Notes (PDF)](Motorsport_Engineering_Reports.pdf)

---

## 4. Lab03 - Sizing the Braking System - Brembo

* Course: Advanced Motorsport Engineering
  * Instructors: Prof. M. Gobbi, Prof. S. Melzi
* Authors: M. Cigada, F. D'Agostini, S. D'Incà
* Academic Year: 2025 - 2026
* Keywords: Brake System Sizing, Brake Disc Sizing, Thermal Model, Brake Balance, Brake Pressure, Driver Force, Bicycle Model, Monza
* Software used: MATLAB, OpenLAP
* Goal of the laboratory: Size the braking system of a formula vehicle by combining thermal and dynamic constraints. The first part focuses on brake disc selection in order to keep disc temperatures within the required operating window over a race stint. The second part defines the hydraulic brake system and brake balance while avoiding rear locking, excessive line pressure, and excessive driver force. Finally, different braking system configurations are compared using a bicycle model simulation to assess their effect on lap time and braking performance.
* [Link to Laboratory Reports and Seminar Notes (PDF)](Motorsport_Engineering_Reports.pdf)

---

## 5. Lab04 - Lap Time Simulator 2

* Course: Advanced Motorsport Engineering
  * Instructors: Prof. M. Gobbi, Prof. S. Melzi
* Authors: M. Cigada, F. D'Agostini, S. D'Incà
* Academic Year: 2025 - 2026
* Keywords: Ride Height, Ground Stiffness, Aerodynamic Maps, Bottoming Constraint, Isochrone Maps, Lift and Coast, Fuel Saving, Brake Energy, Race Simulation
* Software used: MATLAB, OpenLAP
* Goal of the laboratory: Extend the lap time simulation workflow by including ride-height-dependent aerodynamics and race strategy considerations. The first part evaluates how static ride heights and ground stiffnesses affect aerodynamic coefficients, aero balance, and lap time, while enforcing feasibility constraints to avoid non-physical aerodynamic-map regions. The second part studies lift-and-coast strategies at Monza, comparing the trade-off between fuel saving, brake energy reduction, and lap time penalty both on single corners and over a 40-lap race simulation.
* [Link to Laboratory Reports and Seminar Notes (PDF)](Motorsport_Engineering_Reports.pdf)

---

## 6. Lab05 - Data Analysis using WinTax - Magneti Marelli

* Course: Advanced Motorsport Engineering
  * Instructors: Prof. M. Gobbi, Prof. S. Melzi
* Authors: M. Cigada, F. D'Agostini, S. D'Incà
* Academic Year: 2025 - 2026
* Keywords: Telemetry Analysis, WinTax, Motorcycle Dynamics, IMU, Coordinate Transformation, Signal Filtering, Lateral Acceleration, Phillip Island, Mugello
* Software used: WinTax
* Goal of the laboratory: Analyze racing motorcycle telemetry data with a focus on acceleration signals. The laboratory defines virtual channels to transform raw IMU measurements from the vehicle frame to an inertial reference frame, compares raw and low-pass-filtered signals, and uses the filtered data to identify the corners with the highest lateral acceleration on the Phillip Island and Mugello circuits.
* [Link to Laboratory Reports and Seminar Notes (PDF)](Motorsport_Engineering_Reports.pdf)

---

## 7. Lab06 - Advanced Lap Time Simulator

* Course: Advanced Motorsport Engineering
  * Instructors: Prof. M. Gobbi, Prof. S. Melzi
* Authors: M. Cigada, F. D'Agostini, S. D'Incà
* Academic Year: 2025 - 2026
* Keywords: Advanced Lap Time Simulation, Optimal Control, Energy Constraint, Lift and Coast, Minimum Lap Time, Racing Trajectory
* Software used: MATLAB
* Goal of the laboratory: Study a minimum lap time problem in which the simulator optimizes vehicle inputs along the track while respecting different imposed energy limits. The comparison between 10 MJ, 12 MJ, and 15 MJ highlights how the optimal driving strategy changes when the available energy is reduced, mainly through earlier throttle lift-off and more extended coast phases, while the optimized racing trajectory remains essentially unchanged.
* [Link to Laboratory Reports and Seminar Notes (PDF)](Motorsport_Engineering_Reports.pdf)

---

## 8. Lab07 - VI-CRT Lap Time Simulator

* Course: Advanced Motorsport Engineering
  * Instructors: Prof. M. Gobbi, Prof. S. Melzi
* Authors: M. Cigada, F. D'Agostini, S. D'Incà
* Academic Year: 2025 - 2026
* Keywords: VI-CRT, VI-grade, Setup Analysis, Telemetry Comparison, Gear Ratios, Downforce, Anti-Roll Bar, Understeer Gradient, DOE, Spring Stiffness
* Software used: VI-CRT / VI-grade, MATLAB
* Goal of the laboratory: Perform a setup analysis of a Dallara F312 car using VI-grade simulation tools. Starting from a baseline configuration, the laboratory evaluates the effect of longer gears, higher downforce, and a stiffer rear anti-roll bar through telemetry and delta-lap-time comparisons. A final design of experiments is used to investigate the influence of front and rear spring stiffness on lap time and to identify favorable setup trends.
* [Link to Laboratory Reports and Seminar Notes (PDF)](Motorsport_Engineering_Reports.pdf)

---

## 9. Motorsport Seminars

* Course: Advanced Motorsport Engineering
  * Instructors: Prof. M. Gobbi, Prof. S. Melzi
* Authors: M. Cigada, F. D'Agostini, S. D'Incà
* Academic Year: 2025 - 2026
* Keywords: Race Engineering, Racing Tires, Sustainability, Formula 1 Setup, Cycling Tires, Racing Motorbikes, Electric Motors, Motorsport Technology
* Software used: None
* Goal of the seminars: Summarize additional insights from invited lectures related to professional motorsport practice. The seminars cover race engineering and team management, racing tire design and data analysis, sustainability in motorsport, Formula 1 vehicle setup, cycling tire performance, racing motorcycle simulation and sensor estimation, and electric motor hardware design for racing applications. These notes are included as complementary material to provide broader industrial context rather than as standalone computational projects.
* [Link to Laboratory Reports and Seminar Notes (PDF)](Motorsport_Engineering_Reports.pdf)

---
