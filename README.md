# RADMC-3D: Interstellar Dust Simulation

## Overview
A three-dimensional dust radiative transfer simulation using RADMC-3D and Python.

This project investigates how radiation from a solar-like star heats a surrounding Gaussian dust cloud and produces thermal infrared emission.

## Simulation Parameters
- Grid: 64 × 64 × 64 cells
- Density model: Gaussian distribution
- Radiation source: Solar-like star (5772 K)
- Method: Monte Carlo Radiative Transfer
- Photon packets: 100,000 and 1,000,000
- Synthetic image wavelength: 100 μm

## Preliminary Results
- Maximum dust temperature: approximately 226.46 K
- Zero-temperature dust cells reduced from 51 to 0
- Synthetic thermal emission image generated at 100 μm

## Tools
- RADMC-3D
- Python
- NumPy
- Matplotlib
- Google Colab

## Scientific Limitations
This is an educational proof-of-concept simulation. Dust opacity is simplified, and further convergence testing and physical validation are needed before using the results for research conclusions.

## Future Work
- Clumpy and filamentary dust structures
- Realistic dust opacity models
- Multi-wavelength synthetic observations
- Quantitative analysis of dust temperature and emission
