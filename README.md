# CIGS Absorber Thickness Optimization

This repository contains the Google Colab notebook associated with the manuscript:

**Blind-Validated Coupled Optical–Electrical Optimization of CIGS Absorber Thickness across the Composition Range**

The notebook implements a coupled optical–electrical model for CuIn1-xGaxSe2 (CIGS) absorber thickness optimization, including:

- two-pass wavelength-dependent optical absorption,
- Urbach-tail correction to sub-bandgap absorption,
- Hegedus–Shafarman / Gärtner carrier collection,
- Green fill-factor model,
- quadratic Shockley–Read–Hall bulk recombination scaling as `(d/L)^2`,
- blind validation against literature CIGS devices,
- sensitivity analysis and final design maps.

## Repository Contents

```text
notebooks/
  CIGS_Optical_Electrical_Model_Final.ipynb

data/
  README.md
