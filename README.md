# AePW3-LDWG

This repository stores the data associated with U-M publications resulting from the Third Aeroelastic Prediction Workshop Large Deflection Working Group.

## Folders associated with Riso and Cesnik, AIAA SciTech Forum, 2022:

* `01_Models_GFEM`: Built-up finite element models for MSC Nastran  
* `02_Models_Beam`: Equivalent beam inertia and stiffness distributions for UM/NAST 
* `03_Modal_Undeformed`: Modal results in undeformed shape 
* `04_Modal_Gravity`: Modal results in statically deformed shape under self weight 
* `05_Static_Bending`: Static bending results due to a tip mass at the midchord point 
* `06_Static_Torsion`: Static torsion results due to a tip mass behind the trailing egde point 
* `07_Static_Aeroelastic`: Static aeroelastic results for AoA = 5, 7 deg
* `08_Linear_Flutter`: Linear flutter analysis (undeformed shape) 
* `09_Nonlinear_Flutter`: Nonlinear flutter analysis for AoA = 0 -> 7 deg

The built-up finite element models with flexible tip rod were originally provided by Prof. Daniella Raveh (Technion). Variants with rigid tip rod were developed at U-M to ease the equivalent beam modeling.

If you use these results, please cite our paper:

Riso, C. and Cesnik, C. E. S., "Low-Order Geometrically Nonlinear Aeroelastic Modeling and Analysis of the Pazy Wing Experiment," AIAA SciTech Forum, San Diego, CA and Online, January 2-7, 2022. AIAA-2022-2313. DOI: https://doi.org/10.2514/6.2022-2313. 

@inproceedings{Riso2022,
	author    = {Cristina Riso and Carlos E. S. Cesnik},
	title     = {Low-Order Geometrically Nonlinear Aeroelastic Modeling and Analysis of the Pazy Wing Experiment},
	booktitle = {AIAA SciTech Forum},
	address   = {San Diego, CA and Online},
	year      = {2022},
	month     = {January 2--7},
	pages     = {1--30},
	note      = {AIAA-2022-231},
	doi       = {10.2514/6.2022-231},
}

Contacts: Cristina Riso (criso@gatech.edu) and Carlos E. S. Cesnik (cesnik@umich.edu)
