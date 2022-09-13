Equivalent beam inertia properties and stiffness properties are given with respect to the beam reference axis at 44% of the chord. 

The coordinates of the beam reference axis nodes are given in coordinates.txt in the MSC Nastran frame but with origin at the wing root. This is not exactly the origin of the MSC Nastran frame in the GFEM because of a small offset.

The equivalent inertia properties are given per beam node. All values are in the MSC Nastran frame. 

Values in a given column are for different beam nodes ("keypoints) root to tip. The meaning of each label is consistent with MSC Nastran CONM2 cards.

mass = rigid-body mass

cgx = rigid-body offset from the node along x
cgy = rigid-body offset from the node along y
cgz = rigid-body offset from the node along z

Ixx = rigid-body xx inertia matrix element about the local C.G. (node position plus offset) 
Iyy = rigid-body yy inertia matrix element about the local C.G. (node position plus offset) 
Izz = rigid-body zz inertia matrix element about the local C.G. (node position plus offset) 
Ixy = rigid-body xy inertia matrix element about the local C.G. (node position plus offset) 
Ixz = rigid-body xz inertia matrix element about the local C.G. (node position plus offset) 
Iyz = rigid-body yz inertia matrix element about the local C.G. (node position plus offset) 

These properties are extracted from the GFEM using 16 reference axis nodes.

Equivalent stiffness properties are given per beam element and they have meaning in the local frame attached to each element. 

Values in a given column are for different beam elements root to tip. The meaning of each label is consistent with the geometrically exact strain-based formulation of Su and Cesnik.

K11 = axial stiffness
K22 = torsion stiffness
K33 = out-of-plane bending stifness
K44 = in-plane bending stiffness

K12 = axial-torsion coupling
K13 = axial-out-of-plane bending coupling
K14 = axial-in-plane bending coupling

K23 = torsion-out-of-plane bending coupling
K24 = torsion-in-plane bending coupling

K34 - out-of-plane-in-plane-bending coupling

For details about how these properties are obtained, see Riso and Cesnik, AIAA SciTech Forum, 2021 & 2022. 

Differently from the Technion Pazy wing, these properties are all obtained on 16 reference axis nodes (instead of a mix of 16 and 6 nodes) because that gave the best frequency comparison.