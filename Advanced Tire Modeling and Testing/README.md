## 1. Vehicle Dynamics

- **Course:** ***Advanced Tire Modeling and Testing***
    - **Instructors:** Prof. E. Sabbioni, Dr. L. Maglia
- **Authors:** G. Biasolo, M. Cigada, F. D'Agostini
- **Date:** September 2025
- **Keywords:** 7-DOF Double-track Model, Magic Formula Tire Modeling, Understeering/Oversteering, Steady-State Behavior, Linear Transient Behavior, Steering Pad, Sine Sweep
- **Software used:** MATLAB, Simulink
- **Goal of the project:** Investigate the influence of different tire sets on vehicle handling dynamics by analyzing linear and non-linear steady-state behaviors and transient responses. The project evaluates how tuning parameters like cornering stiffness and relaxation lengths can transition a vehicle's behavior

* [Link to Project Report (PDF)](ATMT_lab01_report.pdf)

---

## 2. Thermal Model

- **Course:** ***Advanced Tire Modeling and Testing***
    - **Instructors:** Prof. E. Sabbioni, Dr. L. Maglia
- **Authors:** G. Biasolo, M. Cigada, F. D'Agostini
- **Date:** October 2025
- **Keywords:** Simplified Thermal Model, MF-Tyre, Steady-State/Transient Handling
- **Software used:** MATLAB, Simulink
- **Goal of the project:** Investigate temperature's impact on tire performance using a simplified thermal model to analyze heat buildup during warmup cycles. It evaluates how parameters like speed, load, and frequency alter peak grip and cornering stiffness while including relaxation length for realistic transient force development. In the end, the impact of including the thermal effects on the vehicle handling during a steering pad and a slalom maneuver are considered

* [Link to Project Report (PDF)](ATMT_lab02_report.pdf)

---

## 3. ABS

- **Course:** ***Advanced Tire Modeling and Testing***
    - **Instructors:** Prof. E. Sabbioni, Dr. L. Maglia
- **Authors:** G. Biasolo, M. Cigada, F. D'Agostini
- **Date:** November 2025
- **Keywords:** ABS, 7-DOF Simulink Model, Tire Parameter Sensitivity Analysis, MF-Tyre, Thermal Model 
- **Software used:** MATLAB, Simulink
- **Goal of the project:** Evaluate the sensitivity of Antilock Braking System (ABS) performance to variations in tire mechanical parameters and thermal conditions. Utilizing a 7-DOF Simulink model, the study quantifies how factors such as peak grip, longitudinal stiffness, and relaxation length influence critical Key Performance Indicators (KPIs) like stopping distance and mean longitudinal acceleration. Additionally, the project integrates a simplified thermal model to analyze how heat generation during high-slip braking maneuvers degrades tire grip and impacts overall vehicle safety and control logic

* [Link to Project Report (PDF)](ATMT_lab03_report.pdf)

---

## 4. Experimental data fitting
- **Course:** ***Advanced Tire Modeling and Testing***
    - **Instructors:** Prof. E. Sabbioni, Dr. L. Maglia
- **Authors:** G. Biasolo, M. Cigada, F. D'Agostini
- **Date:** December 2025
- **Keywords:** MF-Tire Model Characterization, Relaxation Length Identification, Numerical Optimization (fmincon), MATLAB Fitting Toolbox, Simplified vs. Extended Magic Formula 
- **Software used:** MATLAB, Simulink
- **Goal of the project:**  Build and characterize an MF-Tire 6.2 model using experimental data collected from drum machine testing. The study focuses on identifying the lateral relaxation length through both time-domain (cross-correlation) and frequency-domain (FRF) analysis to capture transient tire behavior. Furthermore, the project implements a custom optimization algorithm using fmincon to fit tire coefficients for longitudinal force, lateral force, and self-aligning moment, comparing the predictive accuracy of simplified versus extended Magic Formula versions under varying vertical loads, camber angles and inflation pressures
* [Link to Project Report (PDF)](ATMT_lab04_report.pdf)

---
