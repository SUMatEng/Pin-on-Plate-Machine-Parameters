### Files Included

- **MATLAB Data set (`.mat` and `.xlsx`):** 
  A data set presenting solved cross-shear ratios and pin rotations over the following multidirectional pin-on-plate machine parameters:
    - Gear radii: 2 to 50 mm
    - Pin radii: 2 to 10 mm 
    - Stroke ranges: 5 to 50 mm 

- **MATLAB Pin-on-Plate Tool (`.zip`):** 
  Unzip this file to access the structured MATLAB folder containing:
  - `data`: Contains parameters used to solve the data set and the solved data set.
  - `scripts`: Contains the main MATLAB scripts:
      - **ConstrainedOptimisationSolver:** Solves machine parameters for specific load cases.
      - **generateCrossShearGrid:** Modify this script to solve for alternative gear radius, pin radius, and stroke ranges beyond those used in the provided data set.
  - `source`: Includes additional files and functions required by the scripts.

- **Python Pin-on-Plate Interpolation Tool (`.ipynb`):** 
   A Python Jupyter notebook that provides a graphical method for interpolating data from the solved data set.

