Natural frequencies given as flow speed (m/s), z displacement (semispan %), freq 1 (Hz), freq 2 (Hz), freq 3 (Hz), freq 4 (Hz), freq 5 (Hz) 

The frequencies are ordered based on the order of the corresponding structural modes in undeformed shape, so they are given considering mode tracking.

The flow speed varies for fixed angle of attack without weight.

Results labeled as UM/NAST are for the beam model coupled with strip theory with spanwise variable aerodynamic coefficient derivatives from the Technion data.

The model is analyzed in the UM/NAST considering different geometrically nonlinear effects, for instance

modal_deformed_aoa7_UM_NAST_sweep = nonlinear kinematics and follower aerodynamics

modal_deformed_aoa7_UM_NAST_sweep_nf = nonlinear kinematics and nonfollower aerodynamics

modal_deformed_aoa7_UM_NAST_sweep_lin = linear kinematics and follower aerodynamics

modal_deformed_aoa7_UM_NAST_sweep_lin_nf = linear kinematics and nonfollower aerodynamics

Results labeled as UVLM are for the beam model coupled with the VLM (UM/NAST-VLM model) and are fully nonlinear (nonlinear kinematics and follower aerodynamics)

Results labeled as GFEM are for the built-up FEM subject to converged UM/NAST-VLM loads analyzed in SOL 400 and are fully nonlinear (nonlinear kinematics and follower aerodynamics)

The last two results above are for the model without skin.