# Data Sources

The optical constants used in this work are based on the experimentally measured CuIn1-xGaxSe2 optical data reported by:

Paulson, P. D., Birkmire, R. W., & Shafarman, W. N.  
Optical characterization of CuIn1-xGaxSe2 thin films by spectroscopic ellipsometry.  
Journal of Applied Physics, 94, 879-888 (2003).  
https://doi.org/10.1063/1.1581345

The raw Paulson optical-constant files are not redistributed in this repository. Users should obtain the original data from the source publication or optical-constants database and place the CSV files in:

data/raw_paulson/

The notebook processes those files into interpolated absorption-coefficient arrays used for the CIGS absorber-thickness optimization.

The validation tables, final design-point tables, S-Q audit, and model-form comparison results generated in this work are included in the `results/` folder.
