# Data README

The optical constants used in this study are based on the experimentally measured CuIn1-xGaxSe2 thin-film optical data reported by:

Paulson, P. D., Birkmire, R. W., & Shafarman, W. N.  
Optical characterization of CuIn1-xGxSe2 thin films by spectroscopic ellipsometry.  
Journal of Applied Physics, 94, 879-888 (2003).  
https://doi.org/10.1063/1.1581345

The raw Paulson optical-constant files are not redistributed in this repository.

To reproduce the notebook calculations, users should obtain the original optical-constant data from the source publication or an appropriate optical-constants database and place the files in the folder path specified in the notebook.

The notebook reads the Paulson files, interpolates the absorption coefficient over wavelength and Ga composition, applies the Urbach-tail correction, and uses the processed absorption coefficients in the CIGS absorber-thickness optimization model.
