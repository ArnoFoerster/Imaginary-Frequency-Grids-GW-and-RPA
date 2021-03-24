# Imaginary-Frequency-Grids-GW-and-RPA

Imaginary Frequency grids and weights for GW and RPA calculations. 
This file is used in the GW and RPA implementations in ADF for imaginary frequency integration.

Structure of the file:
each entry start with 1_xkN_number: The number N denote the number of grid point and weights. 
It goes from 1 to a maximum of 42.
The number after the _ is the range of (KS) orbital energies for which the grid points have been calculated 

Next, there are the N weights and N points.
The last number is the root-mean square error of the grid as compared to the analytical solution. 

The grids have been generated according to:

Kaltak et al., dx.doi.org/10.1021/ct5001268 | J. Chem. Theory Comput. 2014, 10, 2498−2507

