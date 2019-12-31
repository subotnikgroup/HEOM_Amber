# heom_amber
Codes for running hierarichal equation of motion. This code is for a simple spin-Boson problem, however the code itself is general.
Reproduces figure 5 of Strumpfer Schulten, JCTC 8, 2808 (2012). 
Help also taken from  Chen, Zheng, Shi, Tan, JCP 131, 094502 (2009)

The details of the parameters are in the file spectra_heom.inp and in the subroutine setup_parameters in the file mod_spectra_heom.f90.

To run, type make (uses gfortran). Run with ./aout. Should take a few seconds. Creates a file rho.out that has the diagonal entries of the density matrix as a function of time.

Let me know if you need any questions.
