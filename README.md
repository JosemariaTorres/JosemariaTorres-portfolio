# Josemaria Torres — Engineering Portfolio

**Mechanical-Electrical Engineer** · SolidWorks CAD · FEM Simulation · FDM 3D Printing  
[LinkedIn](https://www.linkedin.com/in/) · [Email](mailto:josemaria.torres.vi@gmail.com)

---

## About

I'm a mechanical engineer specializing in SolidWorks CAD modeling, FEM structural simulation, and FDM product development. This repository collects my academic and independent engineering projects — each documented with design rationale, simulation results, and real-world validation where applicable.

---

## Projects

### Academic Projects

---

#### Numerical Modeling of a Composite Mountain Bike Frame
**Bachelor's Thesis · USAT, 2022**

![Thesis cover or FEM result image](images/thesis_cover.png)
*[Image: FEM stress plot or cover page of the thesis document]*

Finite element analysis of a composite MTB frame (polymeric fiber / plastic matrix) under UNE-EN 14766 standard load cases. Includes global stiffness matrix assembly and static condensation implemented in MATLAB.

- **Tools:** MATLAB, SolidWorks
- **Standard:** UNE-EN 14766
- **Status:** Full document available

📄 [Read on Zenodo](https://doi.org/10.5281/zenodo.16945197)

---

#### 5 kW Wind Turbine Drivetrain — Power Transmission Design
**Undergraduate Course Project**

![Wind turbine drivetrain case study image](images/wind_turbine_cover.png)
*[Image: planetary gear CAD render or Von Mises stress plot from the case study PDF]*

Mechanical design and validation of a power transmission system for a 5 kW horizontal-axis wind turbine. Covers shaft sizing, fatigue analysis (Goodman, Gerber, Von Mises, Tresca), planetary gear design, bearing selection, and kinematic validation via motion study. Analytical and simulation results show 2.17% deviation.

- **Tools:** SolidWorks, SolidWorks Simulation, Excel
- **Status:** Case study document available

📄 [View Case Study](undergraduate-projects/Wind_Turbine_5KW/)

---

#### Static FEM Analysis — Trek Supercaliber Frame
**Undergraduate Course Project · Reconstructed**

![Trek Supercaliber FEM stress plot](images/trek_fem.png)
*[Image: Von Mises stress plot of the Trek Supercaliber frame in SolidWorks Simulation]*

Reconstructed FEM case study of the Trek Supercaliber full-suspension mountain bike frame. Static structural analysis under real-world load conditions. CAD model available as a simplified sample due to partial data loss.

- **Tools:** SolidWorks, SolidWorks Simulation
- **Status:** CAD sample + simulation results available

📁 [View Project](undergraduate-projects/Trek_Supercaliber_FEM/)

---

### Independent Engineering Projects

---

#### ADXL345 Removable Clip Mount — Input Shaping Calibration
**Constraint-Driven Design · Artillery Hornet FDM Printer**

![ADXL clip mounted on printer bed](images/adxl_clip_mounted.png)
*[Image: photo of the clip mounted on the Artillery Hornet print bed with ADXL345 sensor attached]*

Designed a removable spring clip to mount an ADXL345 accelerometer on an Artillery Hornet FDM printer for Klipper input shaping calibration. The printer has no dedicated sensor mount — the clip seats on two geometrically different surfaces (print bed stack and X-axis carriage metal plates) using a single aperture. Validated with FEM in SolidWorks Simulation and confirmed with real Klipper resonance data.

- **Tools:** SolidWorks, SolidWorks Simulation, Klipper
- **Material:** PLA+ (FDM printed)
- **Result:** MZV shaper · X: 62.2 Hz · Y: 34.8 Hz · Max accel: 11,400 mm/s²

📄 [View Case Study](independent-projects/ADXL_Clip_Mount/)

---

#### ESP32 + SCD41 Humidity Sensor Enclosure
**Functional Prototype · Environmental Monitoring**

![ESP32 SCD41 enclosure render or photo](images/esp32_enclosure.png)
*[Image: SolidWorks render or photo of the printed enclosure with sensor installed]*

Designed a functional FDM enclosure for an ESP32 microcontroller and SCD41 CO₂/humidity sensor. Design focuses on passive condensate management and sensor accessibility. Validated through analytical methods (Young-Laplace, Hagen-Poiseuille, Rayleigh number analysis) and SolidWorks Flow Simulation.

- **Tools:** SolidWorks, SolidWorks Flow Simulation
- **Material:** PLA+ (FDM printed)
- **Status:** V2 design in validation

📄 [View Case Study](independent-projects/ESP32_SCD41_Enclosure/)

---

#### Captain America Shield — Functional FDM Prop
**Product Design · Additive Manufacturing**

![Captain America shield finished photo](images/shield_finished.png)
*[Image: finished painted shield — the best photo you have of the final product]*

Fully original SolidWorks design of a functional Captain America shield optimized for FDM printing on a domestic printer. Modular construction (25 parts), parametric scaling, and hybrid joint system (E6000 + cyanoacrylate + mechanical fasteners). Validated through real active use. Full design files not publicly available.

- **Tools:** SolidWorks
- **Material:** PLA+, Rust-Oleum + Montana metallic paints
- **Print time:** ~46 hours accumulated

📄 [View Project Overview](independent-projects/Captain_America_Shield/)

---

## Tools & Skills

| Area | Tools |
|---|---|
| CAD Modeling | SolidWorks |
| FEM Simulation | SolidWorks Simulation, ANSYS Fluent |
| CFD | SolidWorks Flow Simulation |
| 3D Printing | OrcaSlicer, FDM (PLA+, PETG) |
| Scripting | MATLAB, Python |
| Documentation | Technical case studies, engineering reports |

---

## Contact

Open to freelance work in CAD modeling, FEM simulation, and FDM product development.  
📧 [your email] · [LinkedIn] · [Upwork]


# JosemariaTorres-portfolio

This repository presents a selection of my academic and creative work, including undergraduate course projects, case studies, and 3D printing projects.

## Bachelor’s Thesis (Spanish Only)

### Numerical Modeling of a Mountain Bike Frame in a Polymeric Fiber / Plastic Matrix Composite for Weight Reduction
https://doi.org/10.5281/zenodo.16945197

**Note:** The CAD files are not available due to data loss; however, the MATLAB code (not uploaded yet) has been rebuilt based on the thesis documentation. 

## Undergraduate Course Projects

### - Static Analysis of the Trek Supercaliber Bicycle Frame (Not uploaded yet)
This is a reconstructed case study. The CAD model is available only as a simplified sample, along with the FEM simulations, due to data loss.

### - 5 kW Wind Turbine Drivetrain – Case Study 
This is a reconstructed case study. The CAD model is not available due to data loss; however, the analysis and design rationale are documented. [View](undergraduated-course-projects/Wind_Turbine_5KW)

## Tovi Lab - 3d printing projects
This portfolio showcases maker projects. [View](tovilab-portfolio)




