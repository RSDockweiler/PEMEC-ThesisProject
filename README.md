# PEMEC-ThesisProject

Collection of everything I have used for my thesis.

twoPhaseEulerIsothermal is the standard twoPhaseEulerFoam, but with the energy equation excluded.

porousV3  is the twoPhaseEulerFoam solver with enchanced two-phase porous treatment - requires inclusion of constant/porousProperties

porousHeatTransferV0 is porousV3 including the total energy equation, modified for the inclusion of a porous layer.

The folder gridConv contains the simulations used for a grid convergence study.

The modelStudy contains a permeability study and a flow regime study.

matlabScripts contains different matlab scripts used for different calculations and plots:
  - GCI_FUNC: Matlab function for GCI test
  - GridOutlet: GCI test at the outlet. Data is obtained from paraview, using the integrate variables filter.
  - heattransfer: Script made for estimating heat transfer from chemical reaction and phase change. Requires polCurve.
  - phaseChange: Script made for estimating phaseChange effect on flow.
  - vanGen: Capillary pressure and relative permeability using the van Genuchten model
  - polCurve: Abritary polarization curve using data from paper or loosely estimated.
  - flow: Script for calculating flow parameters
  - flowMap: Script for estimating flow regimes
  - blockMesh: Script for blockMesh parameters
  - grading: Addition to blockMesh, predicting grading
  - dimNumbers: Script for global dimensionless numbers
  - reynoldsNumber: Estimating Re at inlet
  
