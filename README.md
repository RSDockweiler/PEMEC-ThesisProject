# PEMEC-ThesisProject

Collection of everything I have used for my thesis.

Solvers include:
  twoPhaseEulerIsothermal is the standard twoPhaseEulerFoam, but with the energy equation excluded.
  porousV3  is the twoPhaseEulerFoam solver with enchanced two-phase porous treatment - requires inclusion of constant/porousProperties
  porousHeatTransferV0 is porousV3 including the energy equation, modified for the inclusion of a porous layer and excluding mechanical energy.

Cases include
  Grid: Cases for grid indp. study
  permeabilityTest: Cases for testing the permeability
  flowRegime: Testing the model in different flow regimes
  Lift: Case including the lift force, with constant C_L = 0.25
  heatTransfer: Case including heat transfer

Chapter 1-4 + App B+D includes all calculations done in the report. Overview:
  fig11_h2prod: Figure of H2 prodution, demand and what technology.
  fig22_polCurve: Abritary polarization curve.
  fig25_BakerOverlay: Overlay to the Baker flow map to illustrate flow regime depending on current density and stoichometry
  fig34_dimNumbers: Relevant global dimensionless numbers evaluated
  fig35_porousMap: Porous regime map from  Lenormand (1990).
  fig36_vanGen: The relative permeability of each phase and the capillary pressure evaluated as a function of the effective saturation using the van Genuchten model.
  fig37_blending: Illustrating linear blending between phases.
  fig38_inletProfile: Laminar inlet velocity profile.
  fig41_steadyState: Illustrating area averaged data over time at the outlet of the domain.
  fig47_MandhaneOverlay: Overlay for the Mandhane flow map to illustrate investigated points.
  fig48_flowRegimeDynamic: Transient data along a line for the flow regime study.
  fig416_heatTransfer: Voltage and heat flux vs the current density.
  fig419_tempHistogram: Histogram of the temperature of each phase in the porous domain.
  fig420_phaseChange: Effects of phase change and the asscociated cooling.
  figB3_GridIndp: Grid independent study using the Grid Convergence Index method.
  figD1_TaitelDukler: Taitel and Dukler flow map.
  taitelAndDuklerFunc: Evaluating flow regime for the taitel and dukler flow map.
  GCI_FUNC: Grid Convergence Index Method.
