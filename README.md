# AePW3-LDWG

This repository stores the data associated with our publications resulting from the Third Aeroelastic Prediction Workshop Large Deflection Working Group.

## Wing models

* `01_Pazy_Technion`: Pazy wing version from Technion (this model is used in the Riso and Cesnik publications)
* `02_Pazy_TU_Delft`: Pazy wing version from TU Delft     

The model folders contain the Nastran GFEMs along with the equivalent beam properties used in our analyses.

The built-up finite element models of the Technion Pazy wing with flexible tip rod were originally provided by Prof. Daniella Raveh (Technion). Variants with rigid tip rod were developed by us to ease the equivalent beam modeling.

The built-up finite element model of the TU Delft Pazy wing with flexible tip rod was originally provided by Christoph Mertens (TU Delft). Again, rigid-tip variants were developed by us to ease the equivalent beam modeling.

Note that the TU Delft Pazy wing Nastran GFEM is without the skin, but its properties are tuned based on the GVT of the Pazy wing model with skin tested at TU Delft. 

## Folders associated with Riso and Cesnik, AIAA SciTech Forum, 2022:

* `01_Modal_Undeformed`: Modal results in undeformed shape 
* `02_Modal_Gravity`: Modal results in statically deformed shape under self weight 
* `03_Static_Bending`: Static bending results due to a tip mass at the midchord point 
* `04_Static_Torsion`: Static torsion results due to a tip mass behind the trailing egde point 
* `05_Static_Aeroelastic`: Static aeroelastic results for AoA = 5, 7 deg
* `06_Linear_Flutter`: Linear flutter analysis (undeformed shape) 
* `07_Nonlinear_Flutter`: Nonlinear flutter analysis for AoA = 0 -> 7 deg

## Folders associated with Riso and Cesnik, IFASD, 2022:

* `01_Static_Aeroelastic`: Static aeroelastic results for AoA = 5, 7 deg
* `02_Linear_Flutter`: Linear flutter analysis (undeformed shape) 
* `03_Nonlinear_Flutter`: Nonlinear flutter analysis for AoA = 0 -> 7 deg
* `04_Dynamic_Aeroelastic`: Nonlinear flutter analysis for AoA = 5, 7 deg

The beam model used for these results is the same as for Riso and Cesnik, AIAA SciTech Forum, 2022.

## Folders associated with Riso and Cesnik, Journal of Aircraft, 2023 (based on the above SciTech paper):

The beam model used for these results is the same as for Riso and Cesnik, AIAA SciTech Forum, 2022.

## References 

If you use the Technion Pazy wing model properties and related analysis results, please cite our papers as appropriate:

Riso, C. and Cesnik, C. E. S., "Low-Order Geometrically Nonlinear Aeroelastic Modeling and Analysis of the Pazy Wing Experiment," AIAA SciTech Forum, San Diego, CA and Online, January 2-7, 2022. AIAA-2022-2313. DOI: https://doi.org/10.2514/6.2022-2313. 

Riso, C. and Cesnik, C. E. S., "Post-Flutter Dynamics of the Pazy Wing Geometrically Nonlinear Benchmark Model," IFASD, Madrid, Spain, June 13-17, 2022. IFASD-2022-073. 

Riso, C. and Cesnik, C. E. S., "Impact of Low-Order Modeling on Aeroelastic Solution Accuracy for Very Flexible Wings," Journal of Aircraft, to appear. 

If you use the TU Delft Pazy wing model properties, please cite this repository as the source.

## Contacts 

Cristina Riso (criso@gatech.edu) and Carlos E. S. Cesnik (cesnik@umich.edu)
