# AePW3 LDWG

This repository stores the data associated with our publications resulting from the Third Aeroelastic Prediction Workshop (AePW3) Large Deflection Working Group (LDWG).

Please refer to each publications for details on how the results are obtained.

In general, displacements are given at the half chord and twist angles are recovered from the differential positions of the leading and trailing edges. 

## Wing models

* `01_Pazy_Technion`: Pazy wing version from Technion 
* `02_Pazy_TU_Delft`: Pazy wing version from TU Delft     

The model folders contain the Nastran GFEMs and the equivalent beam properties used in our analyses.

The built-up finite element models of the Technion Pazy wing with flexible tip rod were provided by Prof. Daniella Raveh (Technion). We developed variants with rigid tip rod to ease the equivalent beam modeling.

The built-up finite element model of the TU Delft Pazy wing with flexible tip rod was provided by Christoph Mertens (TU Delft). Again, we developed rigid-tip variants for equivalent beam modeling.

Note that the TU Delft Pazy wing Nastran GFEM is without the skin, but its properties were tuned at TU Delft based on the GVT of the TU Delf Pazy wing with skin.

Please note that we were not involved in the updating of these built-up FEMs. If you have questions regarding that, please contact Prof. Daniella Raveh (Technion Pazy wing) or Christoph Mertens (TU Delft Pazy wing). 

We used an earlier version of the Pazy wing, known as Pre-Pazy wing, in our SciTech 2021 paper. That wing model is not included here because it was discontinued. 

## Riso and Cesnik, AIAA SciTech Forum, 2022

The results reported in this paper have been published in an extended and revised form in Riso and Cesnik, Journal of Aircraft, 2023. You may want to refer to that paper for the most up-to-date and extensive set of results.

* `01_Modal_Undeformed`: Modal results in undeformed shape 
* `02_Modal_Gravity`: Modal results in statically deformed shape under self weight 
* `03_Static_Bending`: Static bending results due to a tip mass at the midchord point 
* `04_Static_Torsion`: Static torsion results due to a tip mass behind the trailing egde point 
* `05_Static_Aeroelastic`: Static aeroelastic results for AoA = 5, 7 deg
* `06_Flutter_Undeformed`: Flutter analysis of undeformed shape 
* `07_Flutter_Deformed`: Flutter analysis of deformed shape for AoA = 0 -> 7 deg

## Riso and Cesnik, IFASD, 2022

The results reported in this paper have been published in an extended and revised form in Riso and Cesnik, Journal of Fluids and Structures, 2023. You may want to refer to that paper for the most up-to-date and extensive set of results.

* `01_Static_Aeroelastic`: Static aeroelastic results for AoA = 5, 7 deg
* `02_Flutter_Undeformed`: Flutter analysis of undeformed shape 
* `03_Flutter_Deformed`: Flutter analysis of deformed shape for AoA = 0 -> 7 deg
* `04_Dynamic_Aeroelastic`: Dynamic aeroelastic results for AoA = 5, 7 deg

The beam model used for these results is the same as for Riso and Cesnik, AIAA SciTech Forum, 2022.

The spanwise-varying aerodynamic coefficient derivatives used for these results are in the static aeroelastic folder.

## Riso and Cesnik, Journal of Aircraft, 2023

* `01_Modal_Undeformed`: Modal results in undeformed shape 
* `02_Modal_Gravity`: Modal results in statically deformed shape under self weight 
* `03_Static_Bending`: Static bending results due to a tip mass at the midchord point 
* `04_Static_Torsion`: Static torsion results due to a tip mass behind the trailing egde point 
* `05_Static_Aeroelastic`: Static aeroelastic results for AoA = 5, 7 deg
* `06_Flutter_Undeformed`: Flutter analysis of undeformed shape 
* `07_Flutter_Deformed`: Flutter analysis of deformed shape for AoA = 0 -> 7 deg

The beam model used for these results is the same as for Riso and Cesnik, AIAA SciTech Forum, 2022.

## Riso and Cesnik, AIAA SciTech Forum, 2023

Please see the journal paper below for these results. 

## Riso and Cesnik, Journal of Fluids and Structures, 2023

For the modal and static structural results, please see Riso and Cesnik, Journal of Aircraft, 2023.

For all the results obtained using UM/NAST with tip loss factors, UM/NAST-VLM, and Nastran solvers also please see Riso and Cesnik, Journal of Aircraft, 2023.

The new results reported in this paper obtained using UM/NAST with spanwise-varying aerodynamic coefficient derivatives and different combinations of geometrically nonlinear effects are given in the following folders.

* `01_Static_Aeroelastic`: Static aeroelastic results for AoA = 5, 7 deg
* `02_Modal_Deformed`: Natural frequencies associated with static aeroelastic results for AoA = 7 deg
* `03_Flutter_Undeformed`: Flutter analysis of undeformed shape 
* `04_Flutter_Deformed`: Flutter analysis of deformed shape for AoA = 0 -> 7 deg
* `05_Dynamic_Aeroelastic`: Dynamic aeroelastic results for AoA = 5, 7 deg

The beam model used for these results is the same as for Riso and Cesnik, Journal of Aircraft, 2023.

The spanwise-varying aerodynamic coefficient derivatives used for these results are in the static aeroelastic folder.

## References 

If you use the Technion Pazy wing model properties and related analysis results, please cite our papers as appropriate:

Riso, C. and Cesnik, C. E. S., "Low-Order Geometrically Nonlinear Aeroelastic Modeling and Analysis of the Pazy Wing Experiment," AIAA SciTech Forum, San Diego, CA and Online, January 2-7, 2022. AIAA-2022-2313. DOI: https://doi.org/10.2514/6.2022-2313. 

Riso, C. and Cesnik, C. E. S., "Post-Flutter Dynamics of the Pazy Wing Geometrically Nonlinear Benchmark Model," IFASD, Madrid, Spain, June 13-17, 2022. IFASD-2022-073. 

Riso, C. and Cesnik, C. E. S., "Impact of Low-Order Modeling on Aeroelastic Predictions for Very Flexible Wings," Journal of Aircraft, 2023. DOI: https://doi.org/10.2514/1.C036869. 

Riso, C. and Cesnik, C. E. S., "Investigation of Geometrically Nonlinear Effects in the Aeroelastic Behavior of a Very Flexible Wing," AIAA SciTech Forum, National Harbor, MD and Online, January 23-27, 2023. AIAA-2023-0759. DOI: https://doi.org/10.2514/6.2023-0759

Riso, C. and Cesnik, C. E. S., "Geometrically Nonlinear Effects in Wing Aeroelastic Dynamics at Large Deflections," Journal of Fluids and Structures, 2023. DOI: https://doi.org/10.1016/j.jfluidstructs.2023.103897.

If you use the TU Delft Pazy wing model properties, please cite this repository.

## Issues

If you have any issues with the models, find mistakes in the uploaded data, or have any questions, please do not hesitate to reach out.

## Contacts 

Cristina Riso (criso@gatech.edu) 

Carlos E. S. Cesnik (cesnik@umich.edu)
