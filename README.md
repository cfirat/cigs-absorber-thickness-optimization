# CIGS Absorber Thickness Optimization

This repository contains the Python/Colab implementation for the manuscript:

**Blind-Validated Coupled Optical–Electrical Optimization of CIGS Absorber Thickness across the Composition Range**

## Contents

- `notebooks/`: final Google Colab notebook
- `data/`: README.md file


## Model Summary

The model couples:
1. Two-pass optical absorption with wavelength-dependent front reflection
2. Hegedus–Shafarman spectral collection
3. Green fill-factor relation
4. Shockley–Read–Hall bulk recombination scaling as `(d/L)^2`

## Requirements

The model was developed and tested in Google Colab using Python 3. The main Python packages are:

numpy
scipy
matplotlib
solcore

## Data Sources
The optical constants are based on the experimentally measured CuIn1-xGaxSe2 optical data reported by Paulson et al. (2003). The repository contains processed and interpolated absorption-coefficient datasets used for reproducibility. The original optical-constant data should be cited through the source publication:

Paulson, P. D., Birkmire, R. W., & Shafarman, W. N. Optical characterization of CuIn1-xGaxSe2 thin films by spectroscopic ellipsometry. Journal of Applied Physics, 94, 879-888 (2003). https://doi.org/10.1063/1.1581345

## Citation
If you use this code, processed data, validation tables, or figures, please cite the associated manuscript and the archived Zenodo DOI.

## License
The code is released under the MIT License.

The processed datasets are shared for reproducibility with attribution to the original optical-constant source. Users should cite Paulson et al. (2003) when using the processed optical data.

## Reproducing Results

Open the notebook:

```text
notebooks/CIGS_Optical_Electrical_Model_Final.ipynb
