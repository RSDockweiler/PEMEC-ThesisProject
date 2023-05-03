# PEMEC-ThesisProject

Collection of everything I have used for my thesis.

twoPhaseEulerIsothermal is the standard twoPhaseEulerFoam, but with the energy equation excluded.

porousV3  is the twoPhaseEulerFoam solver with enchanced two-phase porous treatment - requires inclusion of constant/porousProperties

porousHeatTransferV0 is porousV3 including the total energy equation, modified for the inclusion of a porous layer.

porousPhaseChangeV0 -

The folder gridConv contains the simulations used for a grid convergence study.

The modelStudy contains different model studies:
  - flow regime study: stratified, plug, slug, annular
  - Permeability study: No porous layer, K = 2.25e-5, K=2.25e11 (gradually increasing, FDarcyLimit = +/- 10e4)
  - heatTransfer: Including energy equation, updated boundary condition at bottom of porous layer to constant flux q, based on chemical reaction.
  - phaseChange: -
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
  
