# Dewesoft Summer Camp 2026

This folder contains the material produced by **Team DEWEHard** during **Dewesoft Summer Camp 2026**.

* Event: Dewesoft Summer Camp 2026
* Authors: Team DEWEHard
  * Aljaž Luznar
  * Dilan Akbaba
  * Matteo Cigada
  * Henry Holme (Team Leader)
  * Martina Gallemí Sánchez
  * Hans Anniste
  * Arthur Porterat
  * Jan Tomšej
  * Jon Theys
  * Alvaro Teijeiro Montoro (Team Mentor)
* Date: August 2026
* Vehicle: MINI 005
* Final score: 148 / 210 pts
* Main topics: DewesoftX setup, vehicle instrumentation, inertial measurements, Polygon, sound measurement, CAN decoding, strain gauges, load cell calibration, vehicle dynamics, resource management
* Tools used: DewesoftX, DS-IMU-N1, SIRIUS DAQ, ECA02 CAN sniffer, microphone, PowerPoint, spreadsheet tools

---

## 00. Final Presentation and Team Material

* Material: Final presentation, marketing video and DSE balance
* Reference: Flavija Bornšek
* Authors: Team DEWEHard
* Main contributors: Aljaž Luznar, Dilan Akbaba, Matteo Cigada, Henry Holme, Martina Gallemí Sánchez, Hans Anniste, Jan Tomšej, Jon Theys
* Date: August 2026
* Score: Presentation 26 / 30 pts; Marketing video 12 / 15 pts; DSE balance 10 / 10 pts
* Keywords: team strategy, final presentation, marketing video, DSE balance, resource management
* Tools used: PowerPoint, video editing tools, spreadsheet tools
* Goal of the material: Summarize the team strategy, the challenge solutions, the main difficulties, the lessons learned and the management of the available DSE resources during the week.
* Presentation PDF: [DEWEHard final presentation](00_Final_Presentation_and_Team_Material/DEWEHard_final_presentation.pdf)
* Presentation PowerPoint: [DEWEHard final presentation](00_Final_Presentation_and_Team_Material/DEWEHard_final_presentation.pptx)
* Marketing video: [DEWEHard marketing video](00_Final_Presentation_and_Team_Material/DEWEHard_marketing_video.mp4)
* DSE balance: [DSE balance](00_Final_Presentation_and_Team_Material/DSE_Balance.xlsx)

---

## 01. Mounting and Setup

* Challenge: Mounting and Setup
* Reference: Jernej Moljk
* Technical lecture: Alberto Boffi
* Authors: Team DEWEHard
* Main contributors: Aljaž Luznar, Dilan Akbaba, Henry Holme, Martina Gallemí Sánchez, Hans Anniste, Arthur Porterat, Jan Tomšej, Jon Theys
* Date: August 2026
* Score: 0 / 15 pts
* Keywords: DewesoftX, DS-IMU-N1, GNSS, INS initialization, DAQ setup, wiring, cable management, vehicle power supply
* Tools used: DewesoftX, DS-IMU-N1, GNSS antenna
* Goal of the challenge: Assemble, connect and validate the vehicle measurement setup before the other dynamic tests. Configure the PC power supply, mount the DS-IMU-N1, place the GNSS antenna, route the cables, define the mounting offsets and check the navigation signals in DewesoftX.
* Repository material: [challenge folder](01_Mounting_and_Setup/)

---

## 02. Engineering Precision Driving

* Challenge: Engineering Precision Driving
* Reference: Jernej Moljk
* Technical lecture: Connor Bligh, Jernej Moljk
* Authors: Team DEWEHard
* Main contributors: Aljaž Luznar, Matteo Cigada, Henry Holme, Hans Anniste, Jan Tomšej, Jon Theys
* Date: August 2026
* Score: 18 / 30 pts
* Keywords: DewesoftX, Polygon, DS-IMU-N1, virtual gates, lap timing, lap counting, speed validation, math channels
* Tools used: DewesoftX, Polygon, DS-IMU-N1
* Goal of the challenge: Create a DewesoftX/Polygon setup for a predefined driving course with virtual gates, lap timing, lap counting and gate-speed validation. Configure the vehicle position tracking, implement math channels for gate and lap validity, build a live driver screen and summarize the valid runs in a runsheet.
* Repository material: [challenge folder](02_Engineering_Precision_Driving/)

---

## 03. Static Sound Measurement

* Challenge: Static Sound Measurement
* Reference: Alen Mirtelj
* Technical lecture: Samuele Ardizio, Fabien Jeandenans
* Authors: Team DEWEHard
* Main contributors: Aljaž Luznar, Matteo Cigada, Henry Holme, Hans Anniste, Jan Tomšej, Jon Theys
* Date: August 2026
* Score: 20 / 20 pts
* Keywords: DewesoftX, Sound Level, SPL, intake noise, frequency weighting, time weighting, microphone setup
* Tools used: DewesoftX, Sound Level module, microphone
* Goal of the challenge: Perform static intake sound measurements and compare different vehicle configurations and sound-level settings. Configure the microphone setup, select frequency and time weighting, record reference and modified configurations, and evaluate the SPL variation between measurements. Vehicle intake modifications are allowed only if safe, non-damaging and fully reversible.
* Repository material: [challenge folder](03_Static_Sound_Measurement/)

---

## 04. CAN Decoding

* Challenge: CAN Decoding
* Reference: Eva Kalšek
* Authors: Team DEWEHard
* Main contributors: Dilan Akbaba, Hans Anniste
* Date: August 2026
* Score: 10 / 20 pts
* Keywords: DewesoftX, CAN bus, ECA02, CAN sniffer, signal decoding, scaling, offsets, vehicle data
* Tools used: DewesoftX, ECA02 CAN sniffer
* Goal of the challenge: Decode vehicle CAN messages from the MINI using DewesoftX and a CAN sniffer. Record CAN logs, identify relevant messages, validate decoded signals through controlled tests, and define the scaling factors and offsets required to create usable vehicle channels.
* Repository material: [challenge folder](04_CAN_Decoding/)

---

## 05. Force Cell Lifting Challenge

* Challenge: Force Cell Lifting Challenge
* Reference: Aleš Vozelj, Matjaž Strniša
* Technical lecture: Aleš Vozelj, Rok Podjed
* Authors: Team DEWEHard
* Main contributors: Aljaž Luznar, Henry Holme, Jan Tomšej, Jon Theys
* Date: August 2026
* Score: 30 / 30 pts
* Keywords: DewesoftX, strain gauges, load cell, force measurement, sensitivity, vehicle lifting
* Tools used: DewesoftX, SIRIUS DAQ, strain gauges
* Goal of the challenge: Design, assemble and configure a self-made load cell for the vehicle lifting test. Select the load cell base and strain-gauge layout, wire the gauges for bridge measurement, configure the force measurement in DewesoftX, define the sensitivity and record the final lifting test data.
* Repository material: [challenge folder](05_Force_Cell_Lifting/)

---

## 06. 0-40-0 Rimac Tribute

* Challenge: 0-40-0 Rimac Tribute
* Reference: Jernej Moljk
* Authors: Team DEWEHard
* Main contributors: Aljaž Luznar, Matteo Cigada, Henry Holme, Jon Theys
* Date: August 2026
* Score: 15 / 20 pts
* Keywords: DewesoftX, DS-IMU-N1, speed trigger, acceleration, braking, math channels, distance estimation, vehicle dynamics
* Tools used: DewesoftX, DS-IMU-N1
* Goal of the challenge: Create a DewesoftX setup to measure the time required for the MINI to accelerate from 0 to 40 km/h and brake back to 0 within a single acquisition file. Define speed-based triggers, create math channels for start time, end time and elapsed time, build a live validation screen and select the best valid acquisition.
* Repository material: [challenge folder](06_0-40-0_Rimac_Tribute/)

---

## 07. Most Efficient Team

* Challenge: Most Efficient Team
* Reference: Teo Podlesnik
* Authors: Team DEWEHard
* Main contributors: Aljaž Luznar, Hans Anniste, Arthur Porterat, Jon Theys
* Date: August 2026
* Score: 5 / 10 pts
* Keywords: fuel consumption, fuel estimation, efficiency, resource management, MINI
* Tools used: -
* Goal of the challenge: Estimate the fuel consumption of the MINI before the final refuelling procedure and manage vehicle usage during the week with fuel efficiency in mind. Compare the submitted fuel-consumption estimate with the verified refuelling amount and the actual fuel efficiency.
* Repository material: not included

---

## 08. Team-Defined Challenge

* Challenge: Team-Defined Challenge
* Authors: Team DEWEHard
* Main contributors: Henry Holme, Jon Theys
* Date: August 2026
* Score: 2 / 10 pts
* Keywords: DewesoftX, SIRIUS DAQ, lateral acceleration, wheel speed, steering angle, G-G plot, vehicle dynamics
* Tools used: DewesoftX, SIRIUS DAQ
* Goal of the challenge: Define and implement a custom measurement challenge based on vehicle dynamic signals. Acquire and visualize heading angle, lateral acceleration, wheel speeds and steering angle, and create plots to support the interpretation of the vehicle dynamic behaviour.
* Repository material: [challenge folder](08_Team_Defined_Challenge/)

---
