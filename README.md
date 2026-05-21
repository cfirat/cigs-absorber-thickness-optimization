# CIGS Absorber Thickness Optimization

This repository contains the Python/Colab implementation for the manuscript:

**Blind-Validated Coupled Optical–Electrical Optimization of CIGS Absorber Thickness across the Composition Range**

## Contents

- `notebooks/`: final Google Colab notebook
- `data/`: processed optical constants and validation tables
- `scripts/`: Python scripts for model execution and figure generation
- `results/`: final numerical outputs
- `figures/`: manuscript figures

## Model Summary

The model couples:
1. Two-pass optical absorption with wavelength-dependent front reflection
2. Hegedus–Shafarman spectral collection
3. Green fill-factor relation
4. Shockley–Read–Hall bulk recombination scaling as `(d/L)^2`

## Reproducing Results

Open the notebook:

```text
notebooks/CIGS_Optical_Electrical_Model_Final.ipynb
