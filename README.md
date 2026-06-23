<div align="center">

# 🌊 Submarine Control System

**Controller Design & Simulation for Submarine Depth Stabilization**

[![MATLAB](https://img.shields.io/badge/MATLAB-R2023a-orange.svg)](https://www.mathworks.com/products/matlab.html)
[![Simulink](https://img.shields.io/badge/Simulink-Simulation-blue.svg)](https://www.mathworks.com/products/simulink.html)
[![License: GPL-3.0](https://img.shields.io/badge/License-GPL--3.0-blue.svg)](LICENSE)

*Control Systems — University of Palermo, 2023*

</div>

---

## 📋 Overview

Design and implementation of a feedback controller to stabilize a submarine model described by differential equations. The project covers the full control engineering workflow: from model linearization to closed-loop simulation in Simulink.

## 🧠 Methodology

| Phase | Description |
|-------|-------------|
| **Linearization** | Derive linearized state-space model around operating point |
| **State-Space Analysis** | Eigenvalue decomposition, mode identification |
| **Transfer Function** | Derivation and pole/zero interpretation |
| **Controller Design** | Tuning via SISO Tool and manual root-locus techniques |
| **Simulation** | Closed-loop validation on both linear and nonlinear plants |

## 📁 Project Structure

```
├── Progetto_controllore.m              # MATLAB controller design script
├── Simulink_simulazione1.slx           # Simulink simulation model
├── controllore.mat                     # Saved controller parameters
├── Progetto_Sottomarino_CA22_03.pdf    # Full project report (Italian)
└── LICENSE
```

## 🚀 How to Run

1. Open **MATLAB**
2. Run `Progetto_controllore.m` to load controller parameters
3. Open `Simulink_simulazione1.slx` and start the simulation

## 👥 Authors

- Giovanni Castelli
- Raoul Renda
- Gabriele Nicolò Costa
- **Antonio Spedito** — [@ashenclock](https://github.com/ashenclock)
- Alessandro Macaluso

## 📜 License

This project is licensed under the GPL-3.0 License — see the [LICENSE](LICENSE) file for details.
