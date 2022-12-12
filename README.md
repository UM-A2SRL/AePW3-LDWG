# AePW3-LDWG

This repository stores the data associated with our publications resulting from the Third Aeroelastic Prediction Workshop (AePW3) Large Deflection Working Group (LDWG).

## Wing models

* `01_Pazy_Technion`: Pazy wing version from Technion (this model is used in the Riso and Cesnik publications to date)
* `02_Pazy_TU_Delft`: Pazy wing version from TU Delft     

The model folders contain the Nastran GFEMs and the equivalent beam properties used in our analyses.

The built-up finite element models of the Technion Pazy wing with flexible tip rod were provided by Prof. Daniella Raveh (Technion). We developed variants with rigid tip rod to ease the equivalent beam modeling.

The built-up finite element model of the TU Delft Pazy wing with flexible tip rod was provided by Christoph Mertens (TU Delft). Again, we developed rigid-tip variants for equivalent beam modeling.

Note that the TU Delft Pazy wing Nastran GFEM is without the skin, but its properties were tuned at TU Delft based on the GVT of the TU Delf Pazy wing with skin.

Please note that we were not involved in the updating of these built-up FEMs. If you have questions regarding that, please contact Prof. Daniella Raveh (Technion Pazy wing) or Christoph Mertens (TU Delft Pazy wing). 

We used an earlier version of the Pazy wing, known as Pre-Pazy wing, in our SciTech 2021 paper. That wing model is not included here because it was discontinued by the AePW3-LDWG. 

## Folders associated with Riso and Cesnik, AIAA SciTech Forum, 2022:

* `01_Modal_Undeformed`: Modal results in undeformed shape 
* `02_Modal_Gravity`: Modal results in statically deformed shape under self weight 
* `03_Static_Bending`: Static bending results due to a tip mass at the midchord point 
* `04_Static_Torsion`: Static torsion results due to a tip mass behind the trailing egde point 
* `05_Static_Aeroelastic`: Static aeroelastic results for AoA = 5, 7 deg
* `06_Flutter_Undeformed`: Flutter analysis of undeformed shape 
* `07_Flutter_Deformed`: Flutter analysis of deformed shape for AoA = 0 -> 7 deg

## Folders associated with Riso and Cesnik, IFASD, 2022:

* `01_Static_Aeroelastic`: Static aeroelastic results for AoA = 5, 7 deg
* `02_Flutter`: Flutter analysis of undeformed shape 
* `03_Flutter`: Flutter analysis of deformed shape for AoA = 0 -> 7 deg
* `04_Dynamic_Aeroelastic`: Nonlinear dynamic analysis for AoA = 5, 7 deg

The beam model used for these results is the same as for Riso and Cesnik, AIAA SciTech Forum, 2022.

## Folders associated with Riso and Cesnik, Journal of Aircraft, 2022, to appear (based on the above SciTech paper):

* `01_Modal_Undeformed`: Modal results in undeformed shape 
* `02_Modal_Gravity`: Modal results in statically deformed shape under self weight 
* `03_Static_Bending`: Static bending results due to a tip mass at the midchord point 
* `04_Static_Torsion`: Static torsion results due to a tip mass behind the trailing egde point 
* `05_Static_Aeroelastic`: Static aeroelastic results for AoA = 5, 7 deg
* `06_Flutter_Undeformed`: Flutter analysis of undeformed shape 
* `07_Flutter_Deformed`: Flutter analysis of deformed shape for AoA = 0 -> 7 deg

The beam model used for these results is the same as for Riso and Cesnik, AIAA SciTech Forum, 2022.

## Folders associated with Riso and Cesnik, AIAA SciTech Forum, 2023, to appear:

Thank you for your interest in these results. We are in the process of finalizing the post-processed data for distribution, and we will complete the upload soon. 

## References 

If you use the Technion Pazy wing model properties and related analysis results, please cite our papers as appropriate:

Riso, C. and Cesnik, C. E. S., "Low-Order Geometrically Nonlinear Aeroelastic Modeling and Analysis of the Pazy Wing Experiment," AIAA SciTech Forum, San Diego, CA and Online, January 2-7, 2022. AIAA-2022-2313. DOI: https://doi.org/10.2514/6.2022-2313. 

Riso, C. and Cesnik, C. E. S., "Post-Flutter Dynamics of the Pazy Wing Geometrically Nonlinear Benchmark Model," IFASD, Madrid, Spain, June 13-17, 2022. IFASD-2022-073. 

Riso, C. and Cesnik, C. E. S., "Impact of Low-Order Modeling on Aeroelastic Predictions for Very Flexible Wings," Journal of Aircraft, to appear. 

If you use the TU Delft Pazy wing model properties, please cite this repository.

## Issues

If you have any issues with the models, or find mistakes in the uploaded data, please do not hesitate to reach out.

## Contacts 

Cristina Riso (criso@gatech.edu) and Carlos E. S. Cesnik (cesnik@umich.edu)
