# Residential Thermal Digital Twin

A data-driven and physics-informed project for modeling the thermal behavior of a residential apartment using real sensor data.

## Overview

This project explores how indoor and outdoor temperature measurements can be used to:

- estimate heat loss indicators
- identify thermal parameters
- build a simplified thermal model of a real home
- validate a residential thermal simulator
- provide a foundation for future control and optimization experiments

## Motivation

Most residential "smart home" systems focus on automation convenience.
This project focuses instead on measurable thermal performance, building intelligence, and physics-based understanding of energy behavior.

## Project Goals

- build a reliable temperature dataset from real sensors
- estimate UA / thermal coefficients
- identify thermal time constants
- develop a validated thermal simulator
- explore future extensions such as PINNs and advanced control

## Repository Structure

- `data/`: raw, processed and sample datasets
- `notebooks/`: exploratory and modeling notebooks
- `src/`: reusable Python modules
- `figures/`: plots used in documentation
- `results/`: exported metrics and summaries
- `docs/`: methodology and assumptions

## Current Status

- [x] multi-point temperature monitoring
- [x] initial heat loss estimation
- [x] thermal coefficient estimation
- [x] validated thermal simulator
- [ ] PINN feasibility study

## Key Outputs

Examples of outputs from the project:

- indoor vs outdoor temperature trends
- heat loss regression results
- simulation vs measured temperature comparison
- event-based thermal loss analysis

## Example Figures

_Add figures here once available._

## How to Run

1. Install dependencies:
   ```bash
   pip install -r requirements.txt```
2. Open the notebooks in order:
* 01_data_exploration.ipynb
* 02_ua_estimation.ipynb
* 03_thermal_parameter_identification.ipynb
* 04_simulator_validation.ipynb

## Notes

This repository is a curated public version of an ongoing residential thermal modeling project.
It is intended as a technical artifact, not as a complete production system.

### Future Work

* 2R2C thermal model
* control-oriented simulation
* PINN-based thermal dynamics modeling
* integration of HVAC runtime / energy measurements