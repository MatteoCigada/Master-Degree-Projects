# Master-Degree-Projects
This repository contains projects/reports delivered during my master degree in Mechanical Enginnering | Automotive and Motorsport Engineering
---

## 1. Experimental Modal Analysis

- **Course:** ***Advanced Dynamics of Mechanical Systems***
  - **Professor:** Prof. R. Corradi, Dr. I. La Paglia
- **Date:** September 2024 - December 2024
- **Keywords:** Experimental Modal Analysis, Cantilever Beam, Light Rail Wheel, Natural Frequencies, Mode Shapes, Frequency Response Functions (FRF), Modal Parameter Identification
- **Software used:** MATLAB
- **Goal of the project:** Analyze the behavior of a cantilever beam and a light rail wheel, through the computation and identification of their modal parameters, validating theoretical models with experimental data

### Methodology & Approach

The project was divided into two main parts:

1.  **Cantilever Beam Analysis (Theoretical & Numerical):**
    * **Theoretical formulations** based on the standing wave solution for bending vibration were applied to derive the characteristic equation
    * **Frequency Response Functions**(FRFs) were computed for various input/output locations, demonstrating concepts like co-located response, reciprocity and non-controllability

2.  **Light Rail Wheel Analysis (Experimental Data & Identification):**
    * Utilized a provided dataset of **experimental inertance FRFs** from a resilient light rail wheel.
    * The **FRF-based multi-mode curve fitting method** was implemented to identify the natural frequencies, mode shapes, and damping ratios from the experimental data.
    * The `lsqnonlin()` MATLAB function was employed for least-squares minimization, with initial guesses derived from experimental FRF peaks and phase diagrams.
    * The analysis considered the impact of accelerometer placement and the non-symmetric suspension of the wheel on the observed FRFs.


This project focused on **[briefly explain the main objective or problem this project addressed]**. We utilized **[mention key methodologies, theories, or approaches used]** to **[explain what you did, e.g., analyze a specific dataset, design a system, develop a policy proposal]**. The primary goal was to **[state the intended outcome or contribution]**. Key findings included **[mention 1-2 significant results or conclusions]**.

* [Link to Project 1 Report (PDF)](./path/to/your/project1_report.pdf)  *(Don't click this link yet, we'll get the actual path in Part 2!)*
* [Link to Project 1 Presentation Slides (PPTX)](./path/to/your/project1_slides.pptx) *(Same here, don't worry about the path yet)*

---

