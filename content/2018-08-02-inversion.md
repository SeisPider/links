---
title: "Seismological inversion codes"
date: 2018-08-02T00:57:40+03:00
anchor: "SeisPider"
weight: 20
---

## Structure

### Full Waveform
- [lasif](http://lasif.net/prerequisites.html): a data-driven end-to-end workflow tool to perform adjoint full seismic waveform inversions.

- [SeisFlow](https://github.com/rmodrak/seisflows): differs from previous open-source software in emphasizing both flexibility and HPC portability. 

- [DSM kernel](https://github.com/IPGP/DSM-Kernel): calculate 3D finite frequency Fréchet sensitivity kernels (or 3D waveform partial derivatives) for 1D reference Earth models using Direct Solution Method.

### Surface wave
- [topo_sp_cu](http://ciei.colorado.edu/Products/): ray theoretic surface wave tomography code.

- [FMTOMO](http://rses.anu.edu.au/~nick/fmtomo.html): The forward problem of traveltime prediction is solved using a multi-stage fast marching method (FMM), which is a sophisticated grid-based eikonal solver.

### SKS
- [splitlab](https://github.com/IPGP/splitlab): a Matlab based GUI to measure the splitting of (teleseismic) shear waves.

- [Pytheas](https://github.com/ispingos/pytheas-splitting): software for local shear-wave splitting analysis
  

### Receiever function
- [rf](https://github.com/trichter/rf): software for local shear-wave splitting analysis

- [hk](http://www.eas.slu.edu/People/LZhu/home.html): Receiver function package (deconvolution and H-k stacking) 

- [ccp](http://www.eas.slu.edu/People/LZhu/home.html): Common-Conversion-Point (CCP) stacking of receiver function

## Source

## Moment tensor
- [MTfit](https://github.com/djpugh/MTfit): a Bayesian forward model inversion code for moment tensor and double-couple source inversion using different data types, based on the Bayesian approach presented in Pugh et al, 2016a and Pugh, 2015. 
