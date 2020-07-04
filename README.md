# AxiCLASS-PT

EFTofLSS non-linear predictions in EDE models 


1) Introduction of the nonlinear_pt module in AxiCLASS
2) Significant changes to the nonlinear module, to accomodate both the functions used by AxiCLASS (based on class 2.9, with HMcode) and the ones used by CLASS-PT (based on class 2.6, without HMcode)
3) Significant changes to the input, transfer, spectra, and output modules
4) Minor changes to the main, class, common, arrays, perturbations, and lensing modules
5) Inclusion of the pt_matrices folder
6) Consistent changes in the python wrapper (setup.py classy.c, classy.pyx, cclassy.pxd)
7) Inclusion of the module fft (.c and .h)
