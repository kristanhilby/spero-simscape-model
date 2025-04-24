# SPERO Stop-Rotor Aircraft Simulation Model

This repository provides the Simulink and Simscape implementation of the **SPERO** (Stop-rotor Propulsion for Efficient Rotary Operation) aircraft model. SPERO is a novel stop-rotor concept designed to combine the vertical takeoff and landing capabilities of helicopters with the efficient cruise performance of fixed-wing aircraft.

The model is intended to support academic research in the areas of hybrid aircraft dynamics, control system design, and rotor transition analysis.

## 📖 Citation

If you use this model in your research, please cite the following paper:

> **Hilby, K., Hunter, I., "SPERO: A Stopped Penta-Rotor UAV for Efficient VTOL and Forward Flight," Journal Name, vol. XX, no. X, pp. XXX–XXX, Year.**  
> Available at: [https://doi.org/10.xxxx/iser.2025.spero](https://www.linkedin.com/in/kristan-hilby/)

> **Hilby, K., Hunter, I., "Analytical and Computational Modeling and Validation of a Stop-Rotor Aircraft," 19th International Symposium on Experimental Robotics (ISER), 2025.**  
> Available at: [https://doi.org/10.xxxx/iser.2025.spero](https://www.linkedin.com/in/kristan-hilby/)

> **Hilby, K., "Design and Control of a Stop-Rotor Aircraft Enabled by Morphing Wings," 2025.**  
> Available at: [https://doi.org/10.xxxx/iser.2025.spero](https://www.linkedin.com/in/kristan-hilby/)

A BibTeX entry will be provided upon publication.

## 🛠️ Model Overview

The SPERO simulation model includes the following core components:

- **Simulink** system-level model for overall aircraft behavior and control
- **Simscape Multibody** components for modeling mechanical dynamics, rotor stop/start, and actuator motion
- **Parametric configuration** to enable scalable mission scenarios (hover, transition, forward flight)

## ✅ Requirements

To run the simulation, the following MATLAB toolboxes are required:

- MATLAB R2023b or later
- Simulink
- Simscape
- Simscape Multibody
- Aerospace Blockset (optional, for advanced functionality)

## 🚀 Usage Instructions

1. Clone or download this repository:
   ```bash
   git clone https://github.com/your-username/spero-stop-rotor-sim.git
   cd spero-stop-rotor-sim
