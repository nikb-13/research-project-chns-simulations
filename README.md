# Pseudospectral Method – Preliminary CHNS Solver

This repository contains Jupyter notebooks for learning and experimenting with pseudospectral methods, with a focus on numerical solvers for Cahn–Hilliard–Navier–Stokes-type systems.

The notebooks are organized into prerequisite material, preliminary experiments, and final experiments.

---

## Repository Structure

```text
.
├── Prerequisite notebooks
│   ├── Stage 0 - Basics.ipynb
│   ├── Stage 01 - DFT.ipynb
│   ├── Stage 02 - Spectral Differentiation in 1D.ipynb
│   ├── Stage 03 - Linear PDEs.ipynb
│   ├── Stage 04 - Nonlinear.ipynb
│   └── Stage 05 - 2D.ipynb
│
├── CHNS solver
│   ├── Experiments
│   │   ├── Results
│   │   ├── CHNS_DD_CH_test.ipynb
│   │   ├── CHNS_DD_Non_linear_test.ipynb
│   │   ├── CHNS_DD_Taylor_Green.ipynb
│   │   ├── CHNS_PS_droplet_dynamics.ipynb
│   │   ├── CHNS_PS_experiments.ipynb
│   │   ├── CHNS_PS_LF.ipynb
│   │   ├── CHNS_PS_validation.ipynb
│   │   ├── ch_phase_separation.gif
│   │   ├── omega_with_contour.gif
│   │   └── phi_animation_dd.gif
│   │
│   └── Final
│       ├── Results
│       ├── CHNS_DD_CH_test_DR.ipynb
│       ├── CHNS_DD_Deformation_experiment.ipynb
│       ├── CHNS_DD_Energy_experiment.ipynb
│       ├── CHNS_DD_FC_Reynolds_number_experiment.ipynb
│       ├── CHNS_DD_Laminar_to_turbulent.ipynb
│       ├── CHNS_DD_one_way_droplet.ipynb
│       ├── CHNS_DD_one_way_droplet_Re_experiment.ipynb
│       ├── CHNS_DD_Single_Fluid.ipynb
│       ├── ch_phase_separation_dr.gif
│       ├── ns_only_vorticity.gif
│       └── one_way_omega_phi.gif
│
└── README.md
```

---

## Project Overview

The main objective of this project is to implement and test numerical solvers for phase-field and fluid-flow models.

The repository is divided into three main parts:

1. **Prerequisite notebooks**  
   These notebooks introduce the numerical and mathematical tools needed for the CHNS solver.

2. **Experimental notebooks**  
   These contain preliminary tests, validation experiments, and exploratory simulations.

3. **Final notebooks**  
   These contain the finalized numerical experiments used for studying phase separation, droplet deformation, energy behaviour, Reynolds number effects, and laminar-to-turbulent flow behaviour.

## Requirements

The notebooks require a Python environment with common scientific-computing packages.

Basic dependencies:

```bash
pip install numpy scipy matplotlib jupyter ipykernel
```

Additional packages may be required depending on the implementation inside individual notebooks.
