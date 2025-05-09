## Overview
This repository provides the Simulink [Simscape](https://www.mathworks.com/products/simscape.html) model of **SPERO** (Stopped Penta-Rotor). SPERO is a novel stop-rotor configuration that uses a flippig wing, an active center of pressure, a quadcopter architecture, and wing latch mechanism to achieve stable forward and reverse transition. The provided model can be used to develop novel control systems or adapted to test different mechanical configurations. 

## Features
- Aerodynamic considerations: Unique VTOL and forward flight aerodynamics equations for lift and drag (include those equations here)
- Independent entities for the base, counterbalances, top rotor, and quadcopter components

## Dependencies
To run the simulation, the following MATLAB toolboxes are required:

- MATLAB R2023b or later
- Simulink
- Simscape
- Simscape Multibody
- Aerospace Blockset (optional, for advanced functionality)
- PX4 Autopilot Support from UAV Toolbox (optional, for integration with external flight controller)

## Model Overview

The SPERO simulation model includes the following core components:

- **Simulink** system-level model for overall aircraft behavior and control
- **Simscape Multibody** components for modeling mechanical dynamics, rotor stop/start, and actuator motion
- **Parametric configuration** to enable scalable mission scenarios (hover, transition, forward flight)

## Usage
1. Clone or download this repository:
   ```bash
   git clone https://github.com/kristanhilby/spero-simscape-model.git
   cd spero-simscape-model

## Citation
If you use this model in your research, please cite the following:

> **Hilby, K., Hunter, I., "SPERO: A Stopped Penta-Rotor UAV for Efficient VTOL and Forward Flight," Journal Name, vol. XX, no. X, pp. XXX–XXX, Year.**  
> Available at: [https://doi.org/10.xxxx/iser.2025.spero](https://www.linkedin.com/in/kristan-hilby/)

> **Hilby, K., Hunter, I., "Analytical and Computational Modeling and Validation of a Stop-Rotor Aircraft," 19th International Symposium on Experimental Robotics (ISER), 2025.**  
> Available at: [https://doi.org/10.xxxx/iser.2025.spero](https://www.linkedin.com/in/kristan-hilby/)

> **Hilby, K., "Design and Control of a Stop-Rotor Aircraft Enabled by Morphing Wings," 2025.**  
> Available at: [https://doi.org/10.xxxx/iser.2025.spero](https://www.linkedin.com/in/kristan-hilby/)

A BibTeX entry will be provided upon publication.

## Pending Improvements
- Dynamic lift and drag coeffients and stall
- - 
