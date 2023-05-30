# PEMEC-ThesisProject

Collection of everything I have used for my thesis.

Solvers include:  <br>
- twoPhaseEulerIsothermal is the standard twoPhaseEulerFoam, but with the energy equation excluded. <br>
- porousV3  is the twoPhaseEulerFoam solver with enchanced two-phase porous treatment - requires inclusion of constant/porousProperties <br>
- porousHeatTransferV0 is porousV3 including the energy equation, modified for the inclusion of a porous layer and excluding mechanical energy.<br>


Cases include: <br>
- Grid: Cases for grid indp. study <br>
- permeabilityTest: Cases for testing the permeability <br>
- flowRegime: Testing the model in different flow regimes <br>
- Lift: Case including the lift force, with constant C_L = 0.25 <br>
- heatTransfer: Case including heat transfer <br>

Chapter 1-4 + App B+D includes all calculations done in the report. Overview: <br>
- fig11_h2prod: Figure of H2 prodution, demand and what technology. <br>
- fig22_polCurve: Abritary polarization curve. <br>
- fig25_BakerOverlay: Overlay to the Baker flow map to illustrate flow regime depending on current density and stoichometry. <br>
- fig34_dimNumbers: Relevant global dimensionless numbers evaluated. <br>
- fig35_porousMap: Porous regime map from  Lenormand (1990). <br>
- fig36_vanGen: The relative permeability of each phase and the capillary pressure evaluated as a function of the effective saturation using the van Genuchten model. <br>
- fig37_blending: Illustrating linear blending between phases. <br>
- fig38_inletProfile: Laminar inlet velocity profile. <br>
- fig41_steadyState: Illustrating area averaged data over time at the outlet of the domain. <br>
- fig47_MandhaneOverlay: Overlay for the Mandhane flow map to illustrate investigated points. <br>
- fig48_flowRegimeDynamic: Transient data along a line for the flow regime study. <br>
- fig416_heatTransfer: Voltage and heat flux vs the current density. <br>
- fig419_tempHistogram: Histogram of the temperature of each phase in the porous domain. <br>
- fig420_phaseChange: Effects of phase change and the asscociated cooling. <br>
- figB3_GridIndp: Grid independent study using the Grid Convergence Index method. <br>
- figD1_TaitelDukler: Taitel and Dukler flow map. <br>
- taitelAndDuklerFunc: Evaluating flow regime for the taitel and dukler flow map. <br>
- GCI_FUNC: Grid Convergence Index Method.
