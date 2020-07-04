# AxiCLASS-PT

EFTofLSS non-linear predictions in EDE models 
(a merger of https://github.com/PoulinV/AxiCLASS and https://github.com/Michalychforever/CLASS-PT, to be interfaced with https://github.com/Michalychforever/lss_montepython for LSS analyses) 


FEATURES:

1) Introduction of the nonlinear_pt module in AxiCLASS
2) Significant changes to the nonlinear module, to accomodate both the functions used by AxiCLASS (based on class 2.9, with HMcode) and the ones used by CLASS-PT (based on class 2.6, without HMcode)
3) Significant changes to the input, transfer, spectra, and output modules
4) Minor changes to the main, class, common, arrays, perturbations, and lensing modules
5) Inclusion of the pt_matrices folder
6) Consistent changes in the python wrapper (setup.py classy.c, classy.pyx, cclassy.pxd)
7) Inclusion of the module fft (.c and .h)


REFERENCES:

- CLASS

- MontePython

- AxiCLASS

- CLASS-PT
https://arxiv.org/abs/2004.10607

- lss_montepython
https://arxiv.org/abs/1909.05277

